---
title: "安全日报 2026-07-16"
date: 2026-07-16 07:30:00 +0800
categories: 安全
tags: [安全, 网络安全, 行业, 日报]
description: 每日安全行业热点聚合
---

## 安全日报 2026-07-16

> 🔥 今日封面：白宫推出AI驱动漏洞清算中心，加速网络修复
> 📊 分类统计：AI安全(15) | 数据安全(6) | 工控安全(5) | 传统安全(10) | 总计 36 条

---

### 🔐 AI安全

- **[白宫推出AI驱动漏洞清算中心，加速网络修复](https://www.freebuf.com/articles/ai-security/490534.html)**
  - 白宫推出AI漏洞清算中心Gold Eagle，协调政府与行业以比对手更快的速度加速漏洞修复，提升网络防御。

- **[工具返回值里藏一段指令就能劫持 LLM Agent：function calling 的信任边界在哪](https://www.freebuf.com/articles/ai-security/490272.html)**
  - Function calling 的返回值注入，不是一个新鲜漏洞，也不是某个框架的特定 bug

- **[你从 HuggingFace 下的模型可能不是原作者上传的：AI 供应链攻击链全拆解](https://www.freebuf.com/articles/ai-security/490271.html)**
  - safetensors、weights_only、版本锁定、行为基线。不完美，但比什么都不做强。

- **[xAI Grok Build / Grok CLI静默上传整库代码至云端](https://www.freebuf.com/articles/490404.html)**
  - Grok CLI被曝静默上传整库代码至云端，用户仅让回复一个单词，它却“偷走”整个仓库，开发者数据面临严重泄露风险。

- **[FreeBuf早报 \| 一封邮件向AI Agent植入持久性虚假记忆；全网扫描瞄准MCP服务器、Claude凭据与AI模型](https://www.freebuf.com/news/490215.html)**
  - 一封邮件即可向AI Agent植入持久性虚假记忆，隐藏痕迹，悄然改变后续回答方向。

- **[「以图鉴势」嘶吼2026网络安全产业图谱重磅发布]()**
  - 2026年3月，嘶吼安全产业研究院正式启动“2026网络安全产业图谱”调研工作，旨在全景呈现中国网络安全产业的发展格局，为政企客户的采购决策提供选品指南，为安全厂商的市场拓展提供方向参考。历时数月，调研团队累计回收有效问卷400余份，经过严格的筛选核实与系统分析，今日正式发布调研结果。这400余家企业构成了中国网络安全产业最具代表性的核心梯队，他们的生存状态、创新实践与战略选择，正是我们观察产业格

- **[“龙虾”来袭，绿盟科技三位一体防御体系，让网络告别 “裸奔” 风险]()**
  - 2026年开年，OpenClaw（俗称“龙虾”）这款本地优先的 AI Agent 自动化平台以燎原之势席卷全球，凭借自然语言指令实现 PC 全功能自动化的能力，成为开发者追捧的工具。其支持15+通信平台、多模型调用、自主任务执行等特性，让效率提升的同时，也埋下了巨大的安全隐患。工信部于2026年3月8日正式发布openclaw安全风险预警通报。这款看似便捷的工具，正成为企业网络安全的“特洛伊木马”

- **[当“小龙虾”潜入内网，如何解决“影子AI”的隐匿危机]()**
  - 近期，OpenClaw（俗称“小龙虾”）这一开源AI智能体因其强大的自主执行能力而迅速爆火，成为众多企业与开发者的效率神器。然而，就在热度持续攀升之际，国家及行业权威机构接连发布重磅预警：这个看似能干的“AI助手”，正因其模糊的信任边界和脆弱的默认安全配置，成为潜伏在企业内网中的高危风险源。从已披露的CVE-2026-25253、CVE-2026-25157到最新的多个供应链投毒事件，多个已知漏洞

- **[绿盟NF防火墙：筑牢OpenClaw安全防线，构筑AI时代安全基石]()**
  - 2026年2月至3月，国家工业和信息化部网络安全威胁和漏洞信息共享平台（NVDB）连续两次发布关于OpenClaw（俗称“龙虾”）的安全预警，明确指出其“信任边界模糊”“配置缺陷易引发网络攻击、信息泄露”，并首次提出针对AI智能体应用的 “六要六不要” 安全建议。紧接着，国家安全部也发布《“龙虾”安全养殖手册》，警示主机被接管、数据被窃取、供应链投毒等原生风险。官方密集发声的背后，是一组触目惊心的

- **[绿盟科技大模型安全白皮书发布：聚焦智能体风险与防护，护您安全“养虾”]()**
  - 3月20日，由中国信息安全测评中心指导，绿盟科技联合中国科学院信息工程研究所编写的《面向智能体时代的大模型安全——Agentic Security一体化安全范式重构与工程实践》白皮书在北京重磅发布，本次发布会汇聚国内人工智能安全领域专家，围绕智能体时代大模型安全的发展态势、风险挑战、技术体系与产品落地等核心议题展开深度研讨，为行业破解智能体安全治理难题、构建一体化安全防护体系提供权威指引与实践路径

- **[Claude Code源码泄露遭利用，攻击者借GitHub散播窃密木马]()**
  - 威胁组织正利用近期Claude Code源代码泄露事件，通过伪造GitHub仓库向用户分发Vidar窃密木马。Claude Code是人工智能公司Anthropic推出的一款终端版AI代理工具，可直接在终端中执行编程任务，作为自主代理实现系统直接交互、大语言模型API调用管理、MCP集成以及持久化记忆等功能。 据悉，Anthropic在发布npm包时因疏忽，意外嵌入了一个大小为59.8MB的Jav

- **[“影子AI”危机？绿盟威胁情报“三把锁”，构筑OpenClaw防御体系]()**
  - 2026年，AI智能体被广泛应用，OpenClaw（俗称“龙虾”）凭借其自主决策与本地执行能力，成为企业与开发者的高频提效工具。然而，近期多家权威安全机构接连发布预警：OpenClaw正面临从供应链投毒到远程控制的多维安全威胁。当内部员工私自部署此类“影子AI”资产，加之部分恶意Skills（插件）存在越权窃取核心数据的行为，传统边界安全防线正面临失效风险。针对这一现状，绿盟科技结合近期实战攻防与

- **[一只AI“龙虾”的冰火一周：从全网追捧到紧急卸载——OpenClaw爆火背后的三大智能体安全风险与应对]()**
  - 一场轰轰烈烈的“养虾运动”，从全网追捧到紧急卸载，只持续了短短一周。二手平台已经出现另一种服务：远程卸载OpenClaw。价格从499元安装到299元卸载[1]，一条“装虾—教虾—卸虾”的产业链迅速形成。第一批“养虾人”的翻车经历[2]也不断出现：·有人授权OpenClaw访问邮箱，结果邮件被批量删除；·有人让AI清理磁盘，结果整个目录被误删；·还有用户因为API Key泄露，一夜之间损失数万美元

- **[各种Claw层出不穷，你的龙虾是否也已沦为“黑客内鬼”？]()**
  - AI智能体工具OpenClaw的爆火，催生出一个现象级的开发者生态。截至2026年3月，与OpenClaw功能属性相同、设计逻辑相似的衍生项目已超300个，成为高效开发范式下的典型代表。但繁荣背后，安全隐患已全面凸显。大量类OpenClaw工具为追求便捷性与自动化，舍弃基础安全设计，导致超13.5万个公网实例处于无防护的“裸奔”状态，黑客自动化扫描、接管攻击已成为现实，原本的生产力工具，正面临沦为

- **[Supply Chain Compromises Impact Nx Console and GitHub Repositories](https://www.cisa.gov/news-events/alerts/2026/05/28/supply-chain-compromises-impact-nx-console-and-github-repositories)**
  - <p>CISA is prioritizing the response to multiple emerging software supply chain intrusion campaigns targeting developer ecosystems Continuous Integration/Continuous Development (CI/CD) pipelines. Thes

---

### 💾 数据安全

- **[公安部通报37款违规应用，电商类占比超七成，小程序不再是 “法外之地”]()**
  - 依据《网络安全法》《个人信息保护法》等法律法规，经公安部计算机信息系统安全产品质量监督检验中心检测，37款移动应用存在违法违规收集使用个人信息情况，具体通报如下：1、未公开收集使用规则。涉及21款移动应用如下：《奇峰商城》（支付宝小程序）、《聚优商城》（微信小程序）、《亿秀分期商城》（支付宝小程序）、《鲜范商城》（微信小程序）、《京机数码手机商城》（支付宝小程序）、《创维官方商城》（支付宝小程序）

- **[嘶吼安全动态\|八部门联合发布《 科技数据安全管理暂行规定》，4月10日起实施 黑客利用像素级SVG技巧隐藏信用卡窃密代码]()**
  - 嘶吼安全动态\|【国内新闻】八部门联合发布《科技数据安全管理暂行规定》，4月10日起实施摘要：明确科技数据分类分级、算法备案、跨境管控等要求，强化科研与算力设施安全。原文链接：http://m.toutiao.com/group/7626936382984700451/腾讯QClaw V2上线“龙虾管家”，全流程防护AI操作安全摘要：默认开启安全防护，覆盖Prompt、技能与脚本执行，实时拦截恶意指

- **[嘶吼安全动态｜中央网信办召开全国网络法治工作会议 设备码钓鱼攻击暴增36倍，新型攻击工具在网上大肆扩散]()**
  - 嘶吼安全动态【国内新闻】上海人工智能实验室发布“珠穆朗玛计划”，打造AI4S全国中枢摘要：上海AI实验室重磅发布“AGI4S 珠穆朗玛计划”，同步推出DeepLink融合算力平台。该计划旨在通过全维度合作打破算力与数据壁垒，为高能物理、疾病诊断等关键科学领域提供自主受控的智能底座。原文链接：https://www.news.cn/tech/20260408/fe5a61186ceb4582bdcf

- **[Twitter Whistleblower Complaint: The TL;DR Version](https://threatpost.com/twitter-whistleblower-tldr-version/180472/)**
  - Twitter is blasted for security and privacy lapses by the company’s former head of security who alleges the social media giant’s actions amount to a national security risk.

- **[Top Google Security Staff Warn Search Data Could Be Hacked if EU Rules Change](https://www.wired.com/story/top-google-security-staff-warn-search-data-could-be-hacked-thanks-to-eu-plans/)**
  - Europe’s pro-competition proposals could see Google Search and Android systems opened up. The company claims there are serious privacy flaws.

- **[Lessons Learned from CISA’s Recent GitHub Leak](https://krebsonsecurity.com/2026/07/lessons-learned-from-cisas-recent-github-leak/)**
  - The Cybersecurity and Infrastructure Security Agency (CISA) has issued a postmortem on a data leak in which a contractor published dozens of internal CISA credentials -- including AWS Govcloud keys --

---

### ⚙️ 工控安全

- **[纵横网络靶场社区正式发布 以虚实融合技术构建工业信息安全实战生态]()**
  - 当前，工业互联网深度融合发展，关键信息基础设施安全防护需求持续攀升，实战型工业信息安全人才短缺、训练场景稀缺、理论与实践脱节等制约行业发展的核心痛点日益凸显。在此背景下，烽台科技打造的聚焦工业信息安全人才培养与生态共建的纵横网络靶场社区正式发布。该平台依托烽台科技十余年工业靶场技术沉淀，以“虚实融合”技术为核心，整合AI智能体、数字孪生等前沿能力，旨在打造工业安全领域“理论+实战+生态”三位一体的

- **[ICE’s Internal Watchdog Is Now Investigating Online Critics](https://www.wired.com/story/ices-internal-watchdog-is-now-investigating-online-critics/)**
  - The Office of Professional Responsibility has opened more than 100 cases over what ICE officials call “incidents of doxing and threats” against ICE employees.

- **[British Police Built a Sprawling Crime-Prediction Machine. Some Results Couldn’t Be Trusted](https://www.wired.com/story/british-police-built-a-sprawling-crime-prediction-machine-some-results-couldnt-be-trusted/)**
  - As UK police embrace the AI revolution, a WIRED investigation reveals the messy inside story of one region’s experiment with predictive analytics.

- **[ClickFix's Mushrooming Ecosystem Demands New Defense Tactics]()**
  - The attack vector is available for rent at scale, and evades AV and EDR, leaving YARA analysis as the best detection option.

- **[Cybercriminals Flock to Healthcare Businesses as Attacks Surge]()**
  - While cyberattacks against hospitals and clinics grew modestly in the first half of 2026, attacks on service providers and other healthcare businesses more than doubled.

---

### 🛡️ 传统安全

- **[规则写了 300 条照样被打穿：WAF 绕过从编码变异到协议走私全拆解](https://www.freebuf.com/articles/defense/490477.html)**
  - WAF 规则写得越多，安全感越强，但被打穿的概率一点没降。

- **[告警响了然后呢：蓝队从告警确认到攻击溯源的实战方法论](https://www.freebuf.com/articles/defense/490473.html)**
  - 告警响了之后的那三十分钟，考验的不是技术，是判断力。

- **[一行未认证请求打满 CVSS 10 分，SonicWall SMA 1000 这两个零日正在被一把梭（CVE-2026-15409 + CVE-2026-15410）](https://www.freebuf.com/articles/vuls/490465.html)**
  - 补丁打完不等于安全了，下一个零日可能已经在路上了。

- **[Kerberos 票据伪造攻防：从金票到钻石票，红队怎么藏蓝队怎么抓](https://www.freebuf.com/articles/defense/490464.html)**
  - Kerberos 票据攻击检测不是靠一条规则就能解决的。

- **[Cursor漏洞：恶意克隆仓库可在Windows上触发代码执行](https://www.freebuf.com/articles/development/490522.html)**
  - Cursor漏洞：Windows上克隆恶意仓库即自动运行git.exe，无需点击直接执行任意代码。

- **[向量嵌入安全-嵌入反转相似性攻击与向量数据库威胁分析](https://www.freebuf.com/articles/mobile/490376.html)**
  - 向量嵌入是压缩表示，不是加密。它们保留了足够的语义信息来实现相似性搜索。

- **[微软 Active Directory 服务 0Day 漏洞遭野外积极利用](https://www.freebuf.com/articles/system/490415.html)**
  - 微软AD FS 0Day漏洞被积极利用，低权限攻击者可获管理员权限，立即修补！

- **[Windows BitLocker 被曝0Day漏洞：攻击者可绕过磁盘加密保护](https://www.freebuf.com/articles/system/490380.html)**
  - 致命漏洞！Windows BitLocker 0Day绕过磁盘加密，物理接触即可窃取数据。

- **[微软发布创纪录的 622 个补丁，包含两个正被利用的 0Day 漏洞](https://www.freebuf.com/articles/system/490319.html)**
  - 微软7月修补创纪录622个漏洞，两个SharePoint与AD FS 0Day已被利用，需立即修补。

- **[2026年7月补丁星期二：史上最大规模更新，单月621个CVE](https://www.freebuf.com/articles/es/490321.html)**
  - 微软7月补丁星期二发布史上最大规模更新，涉及621个CVE，两个零日漏洞被积极利用，包括AD FS权限提升和SharePoint未认证远程攻击，Hyper-V、RDP等关键漏洞风险极高，需紧急修补。

*每日自动更新 · 来源: FreeBuf · 嘶吼 · 安全脉搏 · CISA · Dark Reading · Threatpost · Wired · CyberScoop · Cyble · KrebsOnSecurity*