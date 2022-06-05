---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605135019-server-side-request-forgery/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Server-side Request Forgery

>[!word] Server-side Request Forgery [SSRF] #fraud
> Happens when an attacker finds a vulnerable web application hosted on a server.
> Attacker sends request to the web server, and web server performs the request on behalf of the attacker 
> - Allows attacker to access services that would orginally be inaccessible (Only the server has access to)

> [!example] SSRF 
> ![SSRF Graphical](https://raw.githubusercontent.com/SheepYY039/PicGo-images/main/img/20220605135600.png)
> 1. Attacker sends a request that controls a web application 
> 2. Web server sends request to another service, such as cloud file storage 
> 3. Cloud storage sends response to Web Server 
> 4. Web Server forwards response to attacker 

> [!example] SSRF #case_study 
> **Capital One SSRF Breach** - March 2019
> - Attacker is able to execute commands on the Capital One Website 
>     - This is normally stopped by a WAF[^1]
>     - The WAF was misconfigured 
> - The attacker obtained security credentials for the WAF role 
> - WAF-Role account listed the buckets on Amazon S3[^2]
> - The buckets included 
>     - Credit card application data from 2005 - 2019
>         - 106 million names, address, phone, email, DoB
>         - 140,000 Social Security numbers 
>         - 80,000 Bank account numbers 

## Causes of SSRF

#cause
- Caused by bad programming #vulnerability 
	- Never trust the user input 
	- Server should validate the input and the responses/ output  
	- The are #rare, but can be critical vulnerabilities 

[^1]: Web Application Firewall
[^2]: Simple Storage Service
