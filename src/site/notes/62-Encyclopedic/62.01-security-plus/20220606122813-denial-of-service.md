---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220606122813-denial-of-service/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Denial of Service

>[!word] Denial of Service [DoS] #attack
> Happens when an attacker forces a service to fail **by overloading the service** 
>- Attackers take advantage of **design failure** or **vulnerability**
>- Cause a system to be unavilable
>    - if a company's server is down, then its [[62-Encyclopedic/62.01-security-plus/20220606155742-competitor|competitor]] can get more users.
>- 轉移你的注意力（create a smokescreen for some other exploit）
>        - 如果他們 take down 你的 DNS Server ，你的經歷會放在拯救 DNS Server 上
>        - 可能就會忽略其他部分
>        - 然後攻擊者就可以實施其他攻擊
>- DoS can be very simple 
>    - An attacker walking up to a building and pulling a power switch 
>    - Thousands of users going on to a website at once 
<!--ID: 1654498554788-->


> [!warning] Prevent DoS 
> 1. Keep your systems patched 

## Friendly DoS

> [!note] 
> 有時後 DoS 可能不是有意的
> - Network DoS 
>     - Plug in the wrong cable to a wrong switch 
>     - Layer 2 loop without [[62-Encyclopedic/62.01-security-plus/20220605181153-spanning-tree-protocol|STP]]
> - Bandwidth DoS 
>     - A user downloading a huge file from a website 
>     - Downloading multi-gigabyte Linux distributions over a DSL line 
> - Physical Stuff 
>     - the Water line breaks 
>         - Get a good shop vacuum 
