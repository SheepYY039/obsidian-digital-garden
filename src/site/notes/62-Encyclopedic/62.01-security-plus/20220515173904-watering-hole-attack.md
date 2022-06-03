---
{"dg-publish":true,"permalink":"/62-encyclopedic/62-01-security-plus/20220515173904-watering-hole-attack/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Watering Hole Attack

> [!word] Watering Hole Attack
> 通过第三者（the watering hole）然后感染 那个水源，期待你们公司的员工自己去跳进陷阱（喝一口水），那你们就有 一个被感染缺口 让对方进入

## 发生情况

1. 你的网络安全的不得了
2. 坏人完全进不了
3. 公司也没有人可以給其他人 access
4. 也没有理会任何 [Phishing](20220513183720-phishing.md) Emails
5. 从来没有打开任何 Email Attachments

## 准备

1. 攻击者需要做资料调查
   1. 了解此公司员工会去哪些网站
   1. 本地咖啡或三民治店
   1. 与该公司有关的同 industry 网站
2. 攻击第三者网站
   1. 找网站漏洞
   2. Email attachments
3. 通常会感染所有到这个网站的人
   1. 他希望该公司员工会是其中一员

## Defense-in-depth

- Layered Defense （跟多层保障）
- Next Generation Firewalls and IPS
  - Stop the network traffic before things get bad

## Case Study

### January 2017

- Watering Holes (The watering hole was sufficiently poisoned )
  - Polish Financial Supervision Authority
  - National Banking and Stock Commission of Mexico
  - State-owned bank in Uruguay
- Visiting the site would download malicious JavaScript Files
  - But only to IP Addresses matching banks and other financial institutions
- The watering hole was discovered
  - Did it work?
  - We don't know

**Defense-in-depth**

- The Polish Financial Supervision Authority attack code was recognized and stopped by generic signatures in Symantec's [anti-virus](20220421233306-antivirus.md) software
