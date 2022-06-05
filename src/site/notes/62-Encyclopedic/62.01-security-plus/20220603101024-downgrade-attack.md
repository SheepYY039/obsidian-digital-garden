---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220603101024-downgrade-attack/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Downgrade Attack

>[!word] Downgrade attack #attack
> Instead of using perfectly good [[62-Encyclopedic/62.01-security-plus/20220602130052-encryption|encryption]], use something that's not so great, to force the systems to downgrade their security. 
<!--ID: 1654406587918-->


>[!example] Downgrade attack 
>2014 - [[62-Encyclopedic/62.01-security-plus/20220605142819-secure-sockets-layer|TLS]] Vulnerability POODLE [^1] 
>- On-path attack 
>- Forces clients to fallback to [[62-Encyclopedic/62.01-security-plus/20220605142819-secure-sockets-layer|SSL]] 3.0 
>- [[62-Encyclopedic/62.01-security-plus/20220605142819-secure-sockets-layer|SSL]] 3.0 has significant cryptographic vulnerabilities 
>- Because of POODLE, modern broswers won't fallback to [[62-Encyclopedic/62.01-security-plus/20220605142819-secure-sockets-layer|SSL]] 3.0

[^1]: Padding Oracle On Downgraded Legacy [[62-Encyclopedic/62.01-security-plus/20220602130052-encryption|Encryption]] 
