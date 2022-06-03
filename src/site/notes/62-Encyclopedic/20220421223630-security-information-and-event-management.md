---
{"dg-publish":true,"permalink":"/62-encyclopedic/20220421223630-security-information-and-event-management/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Security Information and Event Management

> [!word] SIEM
> SIEM is a combination of useful systems used for monitoring and analyzing.
>
> 負責收集和分析網絡裡相關的安全數據，目的是：
>
> 1. 尋找異常行為
> 2. 尋找可疑的攻擊

> [!note]
> Currently, as Big data is getting more popular, some security companies have suggested the idea of Security Data Center (SDC) 安全大數據中心, to collect all security data. SIEM can then be build on top of the SDC, which allows SIEM to make use of SDC's ability to analyze and express data, under conditions with large amount of data.

## SIEM 分析輸出方式

1. 製作有關 incident 和 event 的報告，有助理解網絡上發生的事件
2. 在有可疑行為（自動檢測、提前手動設置）時，立即發出訊息提醒

## SIEM 運作流程

A standard SIEM consists of the following blocks:

1. Log Management System (LMS) 日志管理
2. Security Information Management (SIM) 安全信息管理
3. Security Event Management (SEM) 安全事件管理

### 收集數據

SIEM 會根據你提前設置的數據源來採集資料，例如：

1. 防火墻
2. 防毒軟件
3. 一般軟件
4. 網絡基建設備（network infrastructure devices）
5. Endpoint
6. 網域控制器（domain controller）
7. DNS Server
8. Router

Other than the above, SIEM will also collect data from log files.

### 整合數據

為了方便之後的分析，SIEM 會先整合數據

1. [[62-Encyclopedic/20220421231816-data-aggregation|Data Aggregation]]
2. [[62-Encyclopedic/20220421231854-data-normalization|Data Normalization]]
3. [[62-Encyclopedic/20220421232017-data-enrichment|Data Enrichment]]

### 建立 Profiles

SIEM 會讓你建立一個 normal profile，就是正常時候（normal conditions）下網絡系統運作是啥樣滴。

然後根據這個 normal profile 去檢測異常行為：

1. 你可以預先設置一些 rules 去 capture 可疑數據
2. 有些 SIEM 可以使用 [[62-Encyclopedic/62.01-security-plus/20220603081429-machine-learning|machine learning]] 去根據日常數據去檢測異常數據
3. Rules and Profiles initially given by the SIEM system

### 分析數據

SIEM 會根據收集到的異常數據去嘗試分析到底發生啥了。

1. 發現 trends
2. 發現 threats

如果你設定以一些 rules 被檢測到了，它也可以通知你。

> [!example] Rules 的例子
> 連續 5 次錯誤密碼輸入

### 幫助後續調查

1. 專業人員可以 query 存在 SIEM 裡的數據去收窄調查範圍
2. Trace back 事件去查 [[62-Encyclopedic/20220419102338-security-incident|Security Incident]] 的 root cause
3. 為他們的結論提供證據
4. Allows data visualization for easier understanding and faster further investigations.

## SIEM 的好處

- Threat Detection
  - Allows for real time detection of threats, even [[62-Encyclopedic/20220421233121-zero-day-threat|zero day threats]], which [[62-Encyclopedic/20220421233306-antivirus|antivirus]] and anti malware solutions cannot do
  - Helps detecting [[62-Encyclopedic/20220421233628-advanced-persistent-threats|Advanced Persistent Threats]]
- Compliance Reporting and Auditing
  - SIEM can aggregate log data and present it in an audit ready format
  - Many SIEMs now automatically provide monitoring and reporting to meet standards like, HIPAA, PCI/DSS, SOX, FERPA, and HITECH.
  - Such information can be directly provided to auditors and regulators
  - To prove that proper safeguards are in place
  - provide confirmation that any [[62-Encyclopedic/20220419102338-security-incident|security incidents]] have been detected and contained
- Forensics and Incident Response
  - Perform quick analysis and correlation of data in the aggreated log files
  - Forensic analysts can easily generate accurate and court admissible evidence
  - Many forensic investigations have the potential to go to court
  - Such data are invaluable
  - Allows you to draw accurate conclusions of what happened during a [[62-Encyclopedic/20220419102338-security-incident|security incident]]

## 成熟 SIEM 工具

Open Source SIEM Tools

1. OSSIM
2. Elastic SIEM
3. Opensoc

## Related

- [What is a SIEM — SecurityMadeSimple](https://www.securitymadesimple.org/cybersecurity-blog/what-is-a-siem)
- [浅析 SIEM、态势感知平台、安全运营中心\_xiejava1018 的博客-CSDN 博客\_siem 安全](https://blog.csdn.net/fullbug/article/details/104620037)
