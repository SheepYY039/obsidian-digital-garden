---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605153333-resource-exhaustion/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Resource Exhaustion

>[!word] Resource Exhaustion
> A specialized DoS attack, may only require **one device** and **low bandwidths** 

> [!example] Resource Exhaustion 
> **ZIP bomb**
> - A 42 kilobyte `.zip` compressed file 
> - Uncompresses to 4.5 petabytes (4,500 terabytes)
> - [[62-Encyclopedic/20220421233306-antivirus|Anti-virus]] will identify these 

> [!example] Resource Exhaustion 
> **DHCP Starvation**
> - Attacker floods a network with IP Address requests 
> - MAC Address changes each time 
> - DHCP server eventually runs out of addresses 
> 
> Switch configurations can rate limit DHCP requests 
