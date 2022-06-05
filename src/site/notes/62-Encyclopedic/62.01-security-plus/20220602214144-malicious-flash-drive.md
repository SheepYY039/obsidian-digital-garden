---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220602214144-malicious-flash-drive/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Malicious Flash Drive

>[!word] Malicious flash drive #physical-attack 
> 一個 帶惡毒軟件的 USB Flash Drive 
> - " 免費的 USB！讓我插進我的電腦看看都有些啥！" 
> - “不，你不想”
> 
> 舊一些的系統會自動 mount 並運行 USB，但是現在都被默認關閉或移除了
<!--ID: 1654406587951-->


>[!warning] Possible problems in a USB 
> - 一些內陷與文件裏的 malware 
> - 可以是一個 boot device 
>     - 當你 reboot 的時候就自動 boot 進去 usb
> - 裝扮成 ethernet adapter 
>     - redirects or modifies internet traffice requests 
>     - act as wireless gateway for other devices 
