---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220603113827-non-persistent-xss-attack/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Non-persistent XSS Attack

>[!word] Non-persistent XSS attack
> Happens when website allows users to run scripts from user inputs, such as user input boxes. 
> - Attacker emails a link that takes advantage of this vulnerability
> - Script embedded in URL will run a script that sends credentials/ sessions IDs/ [[62-Encyclopedic/62.01-security-plus/20220319074837-cookies|cookies]] to the attacker
>     - As if it came from the [[62-Encyclopedic/20220318223525-server|server]] 
> - Attacker uses credentials/session IDs/[[62-Encyclopedic/62.01-security-plus/20220319074837-cookies|cookies]] to steal victim's information without their knowledge 
>     - very sneaky 
