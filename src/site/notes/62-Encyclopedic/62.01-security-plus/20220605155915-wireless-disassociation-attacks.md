---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220605155915-wireless-disassociation-attacks/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Wireless Disassociation Attacks

>[!word] Wireless Disassociation
> **This is a significant wireless DoS Attack**
> When a you are using a wireless network, and then it suddenly disappears, then it comes back, and it happens again. 
> - You may not be able to stop it 
> - There is (almost) nothing you can do 

> [!example ] Wireless Disassociation Attack 
> Sending **disassociation frames** using 
> `aireplay-ng -0 100 -a <BSSID> -c <STATION> wlan0mon`
> As long as I continue sending, the device is not going to be able to reconnect to the network 
![Wireless Disassociation Attacks - SY0-601 CompTIA Security+ : 1.4 - YouTube](https://youtu.be/qJzhe1r_bK4?list=PLG49S3nxzAnkL2ulFS3132mOVKuzzBxA8&t=170)

> [!info] Protecting against deauth attcks 
> [[62-Encyclopedic/62.01-security-plus/20220605160237-80211-management-frames|802.11 Management Frames]]
> - IEEE has already addressed the problem 
>     - 802.11w - July 2014
> - Some of the important management frames are encrypted 
>     - Disassociate 
>     - Deauthenticate 
>     - Channel Switch announcements 
>     - etc.
> - Not everything is encrypted (so you can first connect to the device) 
>     - Beacons 
>     - Probes 
>     - Authentication 
>     - Association 
> 
> This update to 802.11w was wrote into the 802.11ac standard 
> - So anything on or after 802.11ac already has this written into your AP 
> - And the attacker cannot use Disassociation or deauthorization to remove you from your network 
