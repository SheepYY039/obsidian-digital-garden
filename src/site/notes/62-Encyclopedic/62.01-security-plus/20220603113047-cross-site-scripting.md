---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220603113047-cross-site-scripting/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Cross-site Scripting

>[!word] Cross-site scripting [XSS] #vulnerability
> - Originally caleld cross-site because of broswer security flaws 
>     - Information from one site could be shared with another 
> - One of the most common web application development errors 
>     - takes advantages of the trust a user has for a site 
>     - Complex and varied 

- A very common vulnerability 

>[!warning] 
>[[62-Encyclopedic/20220516095203-malware|Malware]]: "You use javascript? Me too!"

- Types 
	- [[62-Encyclopedic/62.01-security-plus/20220603113827-non-persistent-xss-attack|Non-persistent XSS attack]]
	- [[62-Encyclopedic/62.01-security-plus/20220603114908-persistent-xss-attack|Persistent XSS attack]]

## Protecting Against XSS

- Be careful when clicking untrusted links 
	- never blindly click in your email inbox. Never. 
- Consider disabling JavaScript 
	- or control with an extension 
	- but this only offers limited protection 
- Keep your browser and applications updated 
	- Avoid the nasty browser vulnerabilities 
- Always validate input 
	- do not allow users to add their own scripts to an input field 
