---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220606131816-ddos-amplification/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# DDoS Amplification

>[!word] DDoS Amplification
> An increasingly common network [[62-Encyclopedic/62.01-security-plus/20220606131444-distributed-denial-of-service|DDoS]] technique. Turning a small attack into a big attack. 
> - Makes use of protocols with little or no [[62-Encyclopedic/20220319080626-authentication|authentication]] or checks 
>     - NTP, DNS, ICMP 
>     - A common example of protocol abuse 
> 

>[!example] DNS Amplification 
>- The query is `dig ANY isc.org @75.75.75.75`   
>- but the response is the large chunk of text returned by the `ANSWER SECTION`
>![DDoS Amplification](https://raw.githubusercontent.com/SheepYY039/PicGo-images/main/img/202206061320190.png)

> [!example] DNS amplification DDoS  
> ![DNS Amplification DDoS](https://raw.githubusercontent.com/SheepYY039/PicGo-images/main/img/202206061328278.png)
> 1. *Botnet C&C* sends a control to the *botnet*
>     1. Asks each *bot* to send the `28 byte` DNS query to the *Open DNS Resolvers*
> 2. The query is small, so the *bots* sent them over the internet to the *Open DNS Resolvers*
> 3. *Open DNS resolvers* receive the query, and the responses are over `1300 characters`  
> 4. All the `Open DNS Resolvers` are going to send the response to the *Web Server* that is spoofed in the original query 
> 5. The large amount of traffic easily overwhelms the *web server* 
