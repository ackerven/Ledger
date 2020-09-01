# Ledger

一个以实现财富自由为目的，帮助科学记账的记账工具。



## 前言

At we all know，要想实现财务自由，就要学会科学记账，但科学记账≠记流水账。我对科学记账的理解是能从每天记的流水账中分析自己的消费情况，了解自己的消费习惯，得出自己的个人财务状况。每周做一个小结，月底做一个分析，年底做一个年度总结。人类的恐惧来源于未知，当我们实时掌握自己的财务状况时，我们会更合理的消费，避免一些不必要的、盲目的和冲动的消费。Ledger 这个项目成立的原因是因为我在学校的时候经常吃外卖，而且经常使用花呗支付，再加上买其他的一些，所以总是超出预算。还有一个原因是因为打算学习前端，正好找个项目练练手。



## 简介

这个项目的思路是基于知乎用户[@小水](https://www.zhihu.com/people/pan-76-91) 的一个[回答](https://www.zhihu.com/question/25048034/answer/714353658) 。只要按照一定的格式记录每天的流水账，即可实现：

+ 实时显示各个钱包的余额
+ 实时显示花呗、白条、信用卡的剩余额度及待还金额
+ 自动统计各个分类的消费金额并生成表格



### 使用说明

[点击跳转 ](https://github.com/Ackerven/Ledger/tree/excel/Excel)


## 发展规划

分三个阶段。

#### 第一阶段

+ 版本代号：0-0.9

+ 记账方式：Excel

+ 目的：解决底层分类、记账逻辑以及验证逻辑的合理性。

#### 第二阶段

##### 测试阶段

+ 版本代号：0.9-1.0
+ 记账方式：Excel 为主，Web 端为辅
+ 目的：测试 Web 端

##### 使用阶段

+ 版本代号：1.0-1.9
+ 记账方式：Web 端

**特别说明：Version 1.0 为 Web 端正式发布**

#### 第三阶段

##### 测试阶段

+ 版本代号：1.9-2.0
+ 记账方式：Web 端为主，客户端为辅
+ 目的：测试客户端

##### 使用阶段

+ 版本代号：2.0-∞
+ 记账方式：按需选择

**特别说明：Version 2.0 为客户端正式发布**

客户端开发顺序：Windows ⟶ Android



## 我有话说

也许有的人说，现在这么多记账软件，何必自己造轮子。真的没必要吗？当我们使用记账软件来记账时，我们就要适应它，而不是它适应我们。相反，自己造轮子，边学习边完善，用着舒服，要什么功能可以自己添加，可以根据自己的需求生成各种报表。再者，我个人认为财务状况，消费习惯这些都是一些比较隐私的内容。试想一下，当你的个人消费习惯数据被一些电商公司拿到时，AI 根据这些数据生成用户画像，每天精准给你推送一些你能消费得起的东西。日积月累，不必要的消费就增多了。当然，青菜萝卜各有所爱。使用各种 APP 与造轮子的利弊见仁见智，只要是自己喜欢的，那就是最好的。
