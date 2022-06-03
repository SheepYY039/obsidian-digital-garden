---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220603114908-persistent-xss-attack/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Persistent XSS Attack

>[!word] Persistent XSS attack
>Anyone visiting the webiste will run that script.  
>- Attacker posts a message to a social network 
>     - which includes the malicious payload 
> - Then the malicious message is now hosted on the website 
> - Then the malicious message is now "persistent", and everyone gets the payload
> 
> Unlike [[62-Encyclopedic/62.01-security-plus/20220603113827-non-persistent-xss-attack|Non-persistent XSS attack]], this does not have a specific target, so it targets all viewers to the page 
> - For social networking, this can spread quickly 
>     - everyone who likes/shares the message can have it posted to their page 
>         - where someone else can view it and propagate it further  

>[!example] Persistent XSS attack 
>June 2017, Aaron Guzman (security researcher)
>- When authenticating with Subaru, users get a token 
>    - but this token never expires (don't do this) 
>- A valid token allowed any service request 
>    - Even adding your email address to someone else's account 
>    - so now you have full access to someone else's car  
>The Subaru had a Persistent XSS vulnerability
