---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220602203501-brute-force-attck/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Brute Force Attck

>[!word] Brute force attck
> 嘗試 every possible [[62-Encyclopedic/20220319080333-passwords|passwords]] 直到 [[62-Encyclopedic/20220419121809-hash|hash]] is matched 
> - 要用很多時間
>     - 如果 [[62-Encyclopedic/20220419121840-hashing-algorithm|hashing algorithm]] 強的話，就需要更久
> - 如果是線上的話
>     - 好慢
>     - 大多帳號在幾次失敗就會鎖
> - 所以大多 attackers 是 offline 攻擊
>     - 獲得 list of users and hashes 
>     - 計算 [[62-Encyclopedic/20220419121809-hash|hash]] ，對比目標 [[62-Encyclopedic/20220419121809-hash|hash]] 
>     - large computational resource requirement 

>[!example] Brute force attack
>![Brute force attack](https://raw.githubusercontent.com/SheepYY039/PicGo-images/main/img/20220602203937.png?token=ANN6KIO6KCNPYSTRPHKMR6TCTCX4M)
