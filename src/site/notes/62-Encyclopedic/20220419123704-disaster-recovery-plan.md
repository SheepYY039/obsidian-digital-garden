---
{"dg-publish":true,"permalink":"/62-encyclopedic/20220419123704-disaster-recovery-plan/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# Disaster Recovery Plan

> [!word] Disaster Recovery
> A document that outlines how an org can get back to full operations following an unplanned incident, including earthquakes, fires, hurricanes, or even cyberattack.

- An unexpected disterbance can have a huge impact on smaller companies, as 40-60% of smaller companies that lose access to operational systems without a DR Plan go out of business.
- 93% 的没有灾难恢复计划的小型机构会在大型数据丢失灾难后的一年内关闭
- 但是 75% 的小型机构还是没有 DR Plan

## DR Plan 的目的

让你的机构可以活得更久一点

## DR Plan 的建立

1. 建立一个小组
   1. 到时候出啥事他们负责
   2. 他们会建立和维护相关的文件和文件历史
2. 要清楚公司里重要的资产
   1. 在灾难后，公司需要什么东西才能继续运作？
   2. 要包括硬件 （大楼、机器、工具、数据、等），知识产权，重要员工之类。
   3. 就是所有没了它公司就不能正常运作的东西，就算是短时间内不能正常运作也要 include
3. 记录每样 asset 的 potential disasters (see [[62-Encyclopedic/20220419141010-common-types-of-disasters|common types of disasters]])
   1. 包括自然灾害和不同黑客攻击和 data breach
      1. 越详细越好
   2. 记得考虑公司地理位置，公司所在的领域，公司的对手等。
   3. 要设计 a tailored plan for at least the top 5 disasters (ranked by likelihood) for each asset you have
4. 为每个可能出现的场景拟定解决办法的计划

> [!tip] 要清楚公司对 downtime 和 data loss 的 tolerance level
> 所以需要清楚：
>
> 1.  Maximum Tolerable Downtime (MTD)
> 2.  Recovery Point Objective (RPO)
> 3.  Recovery Time Objective (RTO)
>
> 有了这些才可以清楚知道在 DR 计划里，什么是 prioritized 的，和**怎么算是一个成功的灾难恢复情景**

> [!Tip] 怎么应对媒体
>
> 1.  跟媒体提前沟通好谁可以发布消息
> 2.  媒体要清楚什么该说什么不该说
> 3.  所有员工必须知道真么可以和媒体说什么不能
> 4.  在我们能完全掌握灾难的影响和实施计划前，尽量减少外界的了解

> [!warning] 就算是在危机情况下，已不能忽略保护 sensitive information
>
> 1.  要建立好正确有效的 [[62-Encyclopedic/20220319080626-authentication|authentication]] methods
> 2.  在灾难发生时未授权人员也照样不能 gain access to sensitive information

## 员工遵守计划

1. 你得先有一队带领的
   1. 参加培训，要知道计划怎么实施和怎么让员工遵守
2. 在某些灾害，设计计划的团队可能没办法和所有员工进行沟通，所以在设计者缺席的情况下，也要有后备人选去执行
3. 最好能在有灾害的情况下也能让大部分员工继续正常工作
   1. 可能是安排好 remote work 和 home office
   2. 例如在 covid 的情况下，原本已经有叫好的 technical structure 的 organizations 就可以很快适应新的工作模式

### 员工沟通计划

1. 应该有多种与员工共同的渠道
2. 所有人的联络资料需要准确
   1. 可以设置一个让员工更改联络方式的系统
   2. 定时提醒员工更新资料
3. 有的是有网络未必最稳定，所以也可以有一份联络方式的 hard copy，在没有 email 的情况下也能将所有讯息同步给下属

### 备用工作地点

![[Pasted-image-20220419134845.png|Pasted image 20220419134845]]

- 在不能使用主要工作地点的情况下，员工可以去备用地点继续工作
- 为了不要浪费这个备用地点，平常可以当做是培训基地、活动地点、开会地点、与客户会面地点、等。
- 最好也能有全面的 work from home 措施

### 更新 DR Plan

1. 就像 fire drill 一样，可以实现真实情况的模拟，让公司所有员工都知道在真实情况下应该怎么做
2. 如果在模拟中出现问题，可以及时修正 DR Plan 确认错误不会再发生
3. 模拟也可以有不同的真实度，可能有些只是和相关人员一同走一遍流程，而有些则是真的把服务器关了，然后让相关人员及时应对

> [!note] 模拟时要留意的东西
>
> 1.  公司能保护所有重要财产
> 2.  有多种与员工沟通的渠道
> 3.  我清楚员工需要做什么应对
> 4.  公司有被培训的指定人员带领实施计划
> 5.  有其他地方做备用工作环境
