---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605151730-directory-traversal/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Directory Traversal

>[!word] Directory Traversal #attack
> Allows attackers to 
> - Read files from a web server that are outside the website's file directory 
> - Users shouldn't be able to browse the Windows Folder 
> 
> May be caused by #cause 
> - Web server software vulnerability
>     - Won't stop users from browsing past the web server root 
> - Web application code vulnerability
>     - Take advantage of badly written code 
>     - `GET http://www.example.com/show.asp?view=../../Windows/system.ini HTTP/1.1`
>         - Allows attackers to use `../`

> [!example] Directory Traversal 
> ![Directory Traversal](https://raw.githubusercontent.com/SheepYY039/PicGo-images/main/img/20220605151854.png) 
> When the user is allowed to browse other parts in the file system, outside of the website server (White section)
