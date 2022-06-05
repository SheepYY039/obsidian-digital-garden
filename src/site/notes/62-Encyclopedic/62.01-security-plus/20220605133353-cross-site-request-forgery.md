---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605133353-cross-site-request-forgery/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Cross-site Request Forgery

>[!word] Cross-site Request Forgery [XSRF] #fraud
> 利用一個 網頁 對用戶的 **信任** 去攻擊。
> - Requests 在用戶不知情的情況下發生
> - 攻擊者借用你的 credentials 去動手腳

> [!example] Cross-site Request Forgery 
> 一個攻擊者使用你**已登入的** 社交媒體帳號去發佈貼文

> [!example] Cross-site Request Forgery 
> 1. Attacker **creates a funds transfer request** 
> 2. Request is sent as a **hyperlink** to a user who **may already be logged into** the bank website 
> 3. Visitor **clicks the link** and unknowingly **sends the transfer request** to the bank website 
> 4. Bank **validates the transfer** and sends the visitor's funds to the attacker 

## What Caused XSRF to Happen?

#cause #web-dev

- Significant web application development oversight 
	- The application should have **anti-forgery techniques added** 
	- Usually a **cryptographic token** to prevent a forgery 

## Difference with XSS Attacks

#difference 
- [[62-Encyclopedic/62.01-security-plus/20220603113047-cross-site-scripting|XSS]] Attack is done cross-site 
- XSS Request Forgery is the attacker using your site to make requests 
	- The attacker is cross-site 
	- but the request is not cross-site 
