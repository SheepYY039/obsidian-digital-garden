---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605172441-cryptographic-nonce/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Cryptographic Nonce

>[!word] Cryptographic Nonce
> An arbitrary number that is only used once in [[62-Encyclopedic/62.01-security-plus/20220602130052-encryption|encryption]]. 
> - Usually a random or pseudo-random number 
> - Commonly used during the login process 
>     - Server gives you a nonce 
>     - Calculate your password hash uring thenonce 
>     - Each password hash sent to the host will be different, so a [[62-Encyclopedic/62.01-security-plus/20220603140229-replay-attack|replay]] won't work 
