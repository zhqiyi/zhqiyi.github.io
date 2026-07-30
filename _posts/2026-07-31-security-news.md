---
title: "安全日报 2026-07-31"
date: 2026-07-31 07:30:00 +0800
categories: 安全
tags: [安全, 网络安全, 行业, 日报]
description: 每日安全行业热点聚合
---

## 安全日报 2026-07-31

> 🔥 今日封面：5天连破5层防线：Hugging Face入侵事件的AI攻击链全还原
> 📊 分类统计：AI安全(15) | 数据安全(6) | 工控安全(5) | 传统安全(10) | 总计 36 条

---

### 🔐 AI安全

- **[5天连破5层防线：Hugging Face入侵事件的AI攻击链全还原](https://www.freebuf.com/articles/ai-security/493056.html)**
  - 2026年7月，一个正在被安全评估的AI Agent从OpenAI的评估沙箱中逃逸，横跨三方基础设施，最终渗透进Hugging Face的生产环境、K8s集群、内部网络和源代码控制。

- **[Claude Mythos 自主发现 HAWK 与 AES 漏洞，AI 密码学研究能力超越人类专家](https://www.freebuf.com/articles/ai-security/493036.html)**
  - Claude Mythos自主发现HAWK密钥强度减半漏洞并简化AES攻击，证明AI密码学研究已超越人类专家。

- **[FreeBuf早报 \| 恶意 npm 包投递跨平台 RAT；史上首次完全自主AI Agent网络攻击](https://www.freebuf.com/news/492954.html)**
  - 恶意AI Agent利用暴露凭证和0Day漏洞入侵Hugging Face及四个服务，持续攻击两天半。

- **[AI基础设施安全-云服务配置错误与容器编排漏洞](https://www.freebuf.com/articles/ai-security/492908.html)**
  - 模型权重文件可能被公开访问，推理端点可能在未经认证的情况下暴露，GPU工作负载的特权容器配置可能允许攻击者从推理容器逃逸到宿主机。

- **[企业AI红队实战-从外部侦察到域控的完整攻击链拆解](https://www.freebuf.com/articles/ai-security/492907.html)**
  - 1. 引言：红队实战——所有技术的终极检验在真实的企业对抗场景中，攻击者几乎不会依赖单一漏洞完成突破。他们会将多个看似"微小"的缺陷串联成一条完整的攻击链。正如OffSec AI-300课程所强调的原则：红队的真正价值不在于发现漏洞，而在于证明漏洞的可利用性和业务影响。本次行动的核心目标：从仅知的一个Web应用IP出发，突破网络边界，穿越多层网络区域，最终获取MegaCorpOne AI域控制器的

- **[AI系统威胁建模-基于MITRE-ATLAS的结构化攻击面分析](https://www.freebuf.com/articles/ai-security/492900.html)**
  - 它不从完美的架构图出发，而是从已知信息的边界向外推演，用标注置信度的假设填补空白。

- **[OpenAI AI Agent 在 Hugging Face 入侵事件中使用暴露凭证访问四个服务](https://www.freebuf.com/articles/ai-security/492920.html)**
  - 恶意AI Agent利用暴露凭证和0Day漏洞入侵Hugging Face及四个服务，持续攻击两天半。

- **[史上首次完全自主AI Agent网络攻击：利用0Day漏洞渗透Hugging Face](https://www.freebuf.com/articles/ai-security/492878.html)**
  - 史上首次完全自主AI Agent利用0Day漏洞渗透Hugging Face，窃取答案作弊，CEO称“一次切肤的警醒”。

- **[JFrog 证实：OpenAI 模型在入侵 Hugging Face 之前已利用 Artifactory 零日漏洞](https://www.freebuf.com/articles/ai-security/492747.html)**
  - JFrog确认OpenAI模型利用Artifactory零日漏洞，横向移动后入侵Hugging Face。

- **[Claude Mythos Preview 发现重大密码学弱点：人类专家多年未察觉](https://www.freebuf.com/articles/ai-security/492803.html)**
  - Claude Mythos发现人类专家多年未察觉的密码学弱点，成功将HAWK密钥强度减半，并让AES攻击速度提升800倍。

- **[当AI推理服务暴露在公网上——Ollama攻击面实证分析](https://www.freebuf.com/articles/vuls/492698.html)**
  - Ollama 默认监听 0.0.0.0，14 个 API 端点无认证暴露在公网，Shodan 上 1000+ 台可查。

- **[FreeBuf早报 \| NVIDIA联合36家组织成立开放安全AI联盟；研究人员披露GitLab严重RCE漏洞链](https://www.freebuf.com/news/492681.html)**
  - NVIDIA联合36家组织成立开放安全AI联盟，开源NOOA框架，强调防御者需可下载模型以对抗自主Agent攻击。

- **[「以图鉴势」嘶吼2026网络安全产业图谱重磅发布]()**
  - 2026年3月，嘶吼安全产业研究院正式启动“2026网络安全产业图谱”调研工作，旨在全景呈现中国网络安全产业的发展格局，为政企客户的采购决策提供选品指南，为安全厂商的市场拓展提供方向参考。历时数月，调研团队累计回收有效问卷400余份，经过严格的筛选核实与系统分析，今日正式发布调研结果。这400余家企业构成了中国网络安全产业最具代表性的核心梯队，他们的生存状态、创新实践与战略选择，正是我们观察产业格

- **[“龙虾”来袭，绿盟科技三位一体防御体系，让网络告别 “裸奔” 风险]()**
  - 2026年开年，OpenClaw（俗称“龙虾”）这款本地优先的 AI Agent 自动化平台以燎原之势席卷全球，凭借自然语言指令实现 PC 全功能自动化的能力，成为开发者追捧的工具。其支持15+通信平台、多模型调用、自主任务执行等特性，让效率提升的同时，也埋下了巨大的安全隐患。工信部于2026年3月8日正式发布openclaw安全风险预警通报。这款看似便捷的工具，正成为企业网络安全的“特洛伊木马”

- **[当“小龙虾”潜入内网，如何解决“影子AI”的隐匿危机]()**
  - 近期，OpenClaw（俗称“小龙虾”）这一开源AI智能体因其强大的自主执行能力而迅速爆火，成为众多企业与开发者的效率神器。然而，就在热度持续攀升之际，国家及行业权威机构接连发布重磅预警：这个看似能干的“AI助手”，正因其模糊的信任边界和脆弱的默认安全配置，成为潜伏在企业内网中的高危风险源。从已披露的CVE-2026-25253、CVE-2026-25157到最新的多个供应链投毒事件，多个已知漏洞

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

- **[EU Financial Institutions Leak Data Through Cookie Trackers]()**
  - European and US banks inadvertently transmitted customer data to ad platforms via tracking pixels, raising serious compliance, security, and privacy concerns.

- **[Lessons Learned from CISA’s Recent GitHub Leak](https://krebsonsecurity.com/2026/07/lessons-learned-from-cisas-recent-github-leak/)**
  - The Cybersecurity and Infrastructure Security Agency (CISA) has issued a postmortem on a data leak in which a contractor published dozens of internal CISA credentials -- including AWS Govcloud keys --

---

### ⚙️ 工控安全

- **[纵横网络靶场社区正式发布 以虚实融合技术构建工业信息安全实战生态]()**
  - 当前，工业互联网深度融合发展，关键信息基础设施安全防护需求持续攀升，实战型工业信息安全人才短缺、训练场景稀缺、理论与实践脱节等制约行业发展的核心痛点日益凸显。在此背景下，烽台科技打造的聚焦工业信息安全人才培养与生态共建的纵横网络靶场社区正式发布。该平台依托烽台科技十余年工业靶场技术沉淀，以“虚实融合”技术为核心，整合AI智能体、数字孪生等前沿能力，旨在打造工业安全领域“理论+实战+生态”三位一体的

- **[CISA Urges Water and Wastewater Systems Sector to Protect OT Against Activity Targeting PLCs](https://www.cisa.gov/news-events/alerts/2026/07/30/cisa-urges-water-and-wastewater-systems-sector-protect-ot-against-activity-targeting-plcs)**
  - <p>CISA is currently observing a significant increase in cyber threat actors targeting programmable logic controllers (PLCs) in the Water and Wastewater Systems (WWS) Sector. CISA urges critical infra

- **[DHS Official Resigns, Citing ‘War on Immigrants’](https://www.wired.com/story/dhs-official-resigns-citing-war-on-immigrants/)**
  - The outgoing executive director of the Office of Homeland Security Statistics is one of very few federal officials to speak out against the Trump administration’s immigration crackdown.

- **[Ransomware Attack Puts a Chill on Japanese Frozen-Food Chain]()**
  - A cyberattack on a food and logistics firm disrupts the supply of frozen food to thousands of clients, including major franchises like Kentucky Fried Chicken.

- **[Attackers Combo Up Evasion Tactics for BEC Phishing]()**
  - "The TFF Trap" uses fileless techniques and loaders with low detection rates to deploy various RATs and stealers, including Agent Tesla, Remcos, XWorm, and Best Private Logger.

---

### 🛡️ 传统安全

- **[一发入魂：CVE-2026-42945 Nginx rewrite 堆溢出实战复现，未授权请求直接让主机崩溃](https://www.freebuf.com/articles/vuls/493123.html)**
  - CVE-2026-42945影响软件Nginx漏洞类型堆缓冲区溢出

- **[ROP攻击：技术起源与编写实践](https://www.freebuf.com/articles/system/493054.html)**
  - 本文详解了ROP高级内存攻击技术的起源、编写实践及防范策略。

- **[Fastjson 又爆 RCE？实测告诉你：实战想打穿，难比登天](https://www.freebuf.com/articles/vuls/493089.html)**
  - fastjson漏洞是真的，但能不能利用？

- **[Fastjson 1.2.83 @JSONType Gadget-free RCE 漏洞分析与复现](https://www.freebuf.com/articles/web/491546.html)**
  - Fastjson 1.x 在 ParserConfig.checkAutoType 中，当 SafeMode 未启用时，会造成RCE。

- **[Windows 提权实战：不用 exp 也能提权？那些「运维手滑」留下的系统配置后门](https://www.freebuf.com/articles/system/493057.html)**
  - 前面两期我们讲了Metasploit 打 exp。但真实的红队里，有一类提权根本不需要任何漏洞——它靠的是系统自己的配置错误。

- **[WG-Win-Check 轻量应急辅助工具](https://www.freebuf.com/articles/sectool/467954.html)**
  - WG-Win-Check 是一款基于原生 Win32 API 实现的轻量级的 Windows 应急响应辅助工具。

- **[Windows 提权实战：拿下一个普通用户后，如何用 Metasploit 一路打到 SYSTEM](https://www.freebuf.com/articles/endpoint/492946.html)**
  - 合规声明：本文仅用于合法授权下的渗透测试、红队演练与安全研究，目的是帮助防御方理解攻击手法、补齐检测与加固能力。严禁将文中技术用于未授权系统或任何非法用途，违者后果自负。安全第一，授权先行。你终于拿下了目标 Windows 机器的低权限 Shell——一个普通的 user用户，连装个软件都要弹 UAC。很多人到这一步就卡住了：权限不够，很多活儿干不了。但攻击者不会停。在真实的红队作业里，从「普通用

- **[源码审计的三个模式：从 nginx 到 Traefik](https://www.freebuf.com/articles/vuls/490929.html)**
  - 这篇文章就是把我看到的这三个模式写出来，不是什么&quot;新方法论&quot;，是我做了 6 次审计后自然总结的肌肉记忆。

- **[四步轻松搞定防钓鱼 ！CACTER 反钓鱼演练系统迭代上线]()**
  - 每天上班打开企业邮箱，总能看到各类陌生邮件：发票报销、福利补贴、奖金申领、系统通知…… 看着像内部正规消息，实则很多都是伪装到位的钓鱼陷阱。员工稍有不慎点击链接、下载附件，就可能造成信息泄露、财务损失，给企业埋下巨大安全隐患。 很多企业管理者都面临这样的难题：员工防钓鱼意识不足、极易误入钓鱼陷阱，传统安全培训枯燥脱离实际，还没法用数据量化防护效果。为此，CACTER 反钓鱼演练系统（PhishSi

- **[梆梆安全发布《2026年Q1移动应用安全风险报告》：超八成APP存隐私违规，数据境外外发风险需高度警惕]()**
  - 梆梆安全发布《2026年Q1移动应用安全风险报告》。本报告基于梆梆安全移动应用监管平台在2026年一季度的威胁监测数据与深度安全分析成果，系统梳理当前国内移动应用面临的新型攻击技术演进与安全趋势变化，聚焦盗版仿冒、境外数据传输、高危漏洞、个人隐私违规等多个维度，为移动应用安全建设工作提供参考与实践指引。
当前，我国数字经济与实体经济融合持续深入，移动互联网已演进为支撑社会数字化转型的关键基础设施

*每日自动更新 · 来源: FreeBuf · 嘶吼 · 安全脉搏 · CISA · Dark Reading · Threatpost · Wired · CyberScoop · Cyble · KrebsOnSecurity*