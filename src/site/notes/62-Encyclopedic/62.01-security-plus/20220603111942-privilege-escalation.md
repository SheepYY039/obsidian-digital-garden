---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220603111942-privilege-escalation/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Privilege Escalation

>[!word] Privilege escalation
> 通過漏洞（bug or design flaw）去獲得 higher-level access to a system
> - 因爲 higher-level access 就是有更多權利
> - 所以這些是 high-priority vulnerability patches 
>     - 應該最快解決的 bug 
>     - 因爲現在所有 user 都是 administrator
> - 有時候不一定是上下的級別更改，也可以是橫向的
>     - 用戶 A 可以獲得用戶 B 的權利

- 通常 [[62-Encyclopedic/20220421233306-antivirus|antivirus]] 會檢查並阻止這些 vulnerability
- 系統本身也會有相應的政策去避免：[[62-Encyclopedic/62.01-security-plus/20220603112648-data-execution-prevention|Data Execution Prevention]] 
- Address space layout randomization 
	- 避免 a buffer overrun at a known memory address 

>[!example] Privilege Evaluation
>  CVE-2020-1530 
>  - Windows Remote Access Elevation of Privilege vulnerability
>  - August 20, 2020
>  - Windows Remote Access 
>      - Server 2008, 2012, 2016, 2019
>      - Windows 7, 8.1, 10
>  - Attacker would execute a program on a victim computer 
>      - Vulnerability in Remote Access would elevate privileges 
