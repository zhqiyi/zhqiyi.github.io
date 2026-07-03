---
title: "安全日报 2026-07-04"
date: 2026-07-04 07:30:00 +0800
categories: 安全
tags: [安全, 网络安全, 行业, 日报]
description: 每日安全行业热点聚合
---

## 安全日报 2026-07-04

> 🔥 今日封面：LLM 通用漏洞：伪造系统标签实现"安全拦截幻觉"攻击
> 📊 分类统计：AI安全(15) | 数据安全(7) | 工控安全(5) | 传统安全(10) | 总计 37 条

---

### 🔐 AI安全

- **[LLM 通用漏洞：伪造系统标签实现"安全拦截幻觉"攻击](https://www.freebuf.com/news/488726.html)**
  - 已确认受影响产品：WorkBuddy、豆包、Kimi。漏洞根源在于 LLM 分层 prompt 架构，理论上影响所有采用分层标签结构的 AI 对话产品。

- **[黑客利用SEO投毒与隐藏HTML代码诱骗AI Agent执行恶意指令](https://www.freebuf.com/articles/ai-security/488755.html)**
  - 黑客利用SEO投毒和隐藏HTML代码欺骗AI执行恶意指令，威胁自动化系统安全。

- **[Nebula AI 渗透测试平台实现漏洞评估自动化](https://www.freebuf.com/articles/ai-security/488756.html)**
  - AI渗透测试工具Nebula实现漏洞自动化评估，支持多模型本地/云端部署。

- **[深扒三款AI编程助手的隐私黑盒：一个暗藏后门，两个清清白白](https://www.freebuf.com/articles/ai-security/488658.html)**
  - 本文通过逆向分析方法，对Claude Code、OpenCode 和 Codex三款主流AI编程助手进行了横向安全与隐私审计，重点关注是否存在地区限制、隐蔽数据采集、遥测机制及敏感权限使用等问题。

- **[Agent Skills检测攻防实战：9种绕过手法与最新防御方案](https://www.freebuf.com/articles/ai-security/488653.html)**
  - 基于最新安全研究与真实攻击案例，全面解析 AI Agent Skills 的检测绕过技术、供应链风险及企业级安全防护体系，为构建可信 Agent 生态提供实践指导。

- **[改一个 JSON 文件就能逃逸沙箱？CBSE 漏洞类打穿整条 AI 编程工具链（CVE-2026-25725）](https://www.freebuf.com/articles/vuls/488649.html)**
  - CBSE 这个洞类我看完最大的感触不是 Claude Code 这个实现失误多离谱，而是整个 AI coding 品类都在用同一套有缺陷的配置层级模型赶时间出货。

- **[JADEPUFFER：首个全流程AI驱动的勒索软件攻击行动](https://www.freebuf.com/articles/ai-security/488747.html)**
  - 首个AI全自动勒索攻击：自主入侵、横向移动、加密数据！

- **[黑客利用 Claude AI 窃取全美音乐节门票的网络安全事件](https://www.freebuf.com/articles/ai-security/488664.html)**
  - 黑客利用Claude AI攻破票务系统，窃取全美音乐节管理员权限！

- **[FreeBuf早报 \| 2026年微软漏洞报告深度解析；JetBrains 曝高危漏洞：身份验证绕过与远程代码执行风险并存](https://www.freebuf.com/news/488604.html)**
  - 微软漏洞总数下降但关键漏洞翻倍，云安全风险激增！

- **[Claude Code被曝使用“Spyware”标记东大用户，解决方案可能是OpenAFW](https://www.freebuf.com/articles/ai-security/488578.html)**
  - OpenAFW只能缓解，要根本解决还得靠开源模型。

- **[从 OpenAnt 看 AI 挖洞流水线：安全验证还停留在季度节奏吗？](https://www.freebuf.com/articles/web/488566.html)**
  - 近期公开的 OpenAnt 研究展示了一条 LLM 驱动的漏洞发现流水线：系统先用代码分解和可达性分析缩小候选范围，再让模型以受限远程攻击者视角验证利用路径，最后在隔离沙箱中自动构建环境、生成脚本并复

- **[当 AI Agent越来越像人，企业该怎么识别“好人坏人”？](https://www.freebuf.com/news/488556.html)**
  - 防住 AI Agent，本质上不是在和攻击者博弈，而是在替真实用户守住他们放在你这里的信任。

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

- **[Top Google Security Staff Warn Search Data Could Be Hacked if EU Rules Change](https://www.wired.com/story/top-google-security-staff-warn-search-data-could-be-hacked-thanks-to-eu-plans/)**
  - Europe’s pro-competition proposals could see Google Search and Android systems opened up. The company claims there are serious privacy flaws.

- **[Warner bill would create federally vetted list for secure, trustworthy AI agents](https://cyberscoop.com/ai-agent-act-senate-draft-bill-mark-warner/)**
  - The bill empowers the FTC to create a registry for sellers of AI agent software certifying their privacy and cybersecurity protections. 
The post Warner bill would create federally vetted list for sec

- **[Lawmakers Demand Answers as CISA Tries to Contain Data Leak](https://krebsonsecurity.com/2026/05/lawmakers-demand-answers-as-cisa-tries-to-contain-data-leak/)**
  - Lawmakers in both houses of Congress are demanding answers from the U.S. Cybersecurity & Infrastructure Security Agency (CISA) after KrebsOnSecurity reported this week that a CISA contractor intention

---

### ⚙️ 工控安全

- **[纵横网络靶场社区正式发布 以虚实融合技术构建工业信息安全实战生态]()**
  - 当前，工业互联网深度融合发展，关键信息基础设施安全防护需求持续攀升，实战型工业信息安全人才短缺、训练场景稀缺、理论与实践脱节等制约行业发展的核心痛点日益凸显。在此背景下，烽台科技打造的聚焦工业信息安全人才培养与生态共建的纵横网络靶场社区正式发布。该平台依托烽台科技十余年工业靶场技术沉淀，以“虚实融合”技术为核心，整合AI智能体、数字孪生等前沿能力，旨在打造工业安全领域“理论+实战+生态”三位一体的

- **[British Police Built a Sprawling Crime-Prediction Machine. Some Results Couldn’t Be Trusted](https://www.wired.com/story/british-police-built-a-sprawling-crime-prediction-machine-some-results-couldnt-be-trusted/)**
  - As UK police embrace the AI revolution, a WIRED investigation reveals the messy inside story of one region’s experiment with predictive analytics.

- **[Iran, Russia, China Target Water Systems for Sabotage]()**
  - Nation-state attackers breach water systems through weak passwords, exposed PLCs, and poor segmentation — not sophisticated malware.

- **[Do CISOs Need a Code of Ethics?]()**
  - Dark Reading Confidential Episode 19: Kickbacks, no-show jobs, "dirty" VCs, and shelf ware — industry expert Robert "RSnake" Hansen explains why he thinks it's time for a CISO code of ethics. It could

- **['Cordyceps': Mushrooming Malicious Pull Requests Threaten Developer Workflows]()**
  - The CI/CD workflow weakness affects Microsoft's Azure Sentinel, Google's AI Agent Development Kit, Apache's Doris analytics database, Cloudflare's Workers SDK, and Python Software Foundation's Black.

---

### 🛡️ 传统安全

- **[Linux 权限维持技术总结](https://www.freebuf.com/articles/web/488672.html)**
  - 在攻防中，权限维持是后渗透阶段的关键，是为了防止由于系统重启、管理员修改密码、漏洞被修复或网络中断而失去对系统的控制，从而留下一系列隐蔽后门的技术。

- **[运维血泪史：官网被植入恶意脚本挂黑产广告，传统防护形同虚设，零信任终端才是治本方案](https://www.freebuf.com/articles/endpoint/488665.html)**
  - 运维人员的办公终端，才是网站安全最容易被忽略的突破口。

- **[开放目录里的威胁狩猎
  ——从攻击者疏忽中发现针对泰国多单位的渗透活动](https://www.freebuf.com/articles/web/488655.html)**
  - 开放目录常被当作受害方的配置失误，但安全测试人员乃至高级持续性威胁（APT）攻击者，同样可能因为一次临时文件服务的疏忽而暴露作业痕迹。

- **[一个零字节 QUIC 包打穿 HAProxy 连接池：CVE-2026-33555 跨协议走私拆解](https://www.freebuf.com/articles/vuls/488648.html)**
  - 不是看单个 CVE 的补丁,是看整个"协议翻译信任边界"这个架构模式本身。

- **[iPhone 将实时预警诈骗风险：iOS 27 推出反社交工程攻击新功能](https://www.freebuf.com/articles/endpoint/488746.html)**
  - iOS 27 实时拦截诈骗！苹果新功能专杀社交工程攻击

- **[VulnHub Infosec_Warrior1 靶机渗透实战 — 初学者的复现之路](https://www.freebuf.com/articles/web/488637.html)**
  - 这篇文章按标准渗透测试流程走了一遍，顺便补充了每个漏洞的原理和防御建议，希望对同阶段的同学有帮助。

- **[从 CVE-2024-40439 看 Windows 蓝牙驱动的攻击面与挖掘思路](https://www.freebuf.com/articles/vuls/488618.html)**
  - 本文以CVE-2024-40439 此为切入点，梳理蓝牙驱动攻击面、漏洞原理与利用思路，并提炼出一套可复用的 Fuzzing 策略与逆向方法论，适合想切入蓝牙安全的研究者阅读。

- **[AsyncRAT攻击活动利用DLL侧加载和ScreenConnect实现隐蔽远程访问](https://www.freebuf.com/articles/488627.html)**
  - AsyncRAT利用DLL侧加载伪装合法软件窃密，90+钓鱼网站持续威胁企业安全。

- **[四步轻松搞定防钓鱼 ！CACTER 反钓鱼演练系统迭代上线]()**
  - 每天上班打开企业邮箱，总能看到各类陌生邮件：发票报销、福利补贴、奖金申领、系统通知…… 看着像内部正规消息，实则很多都是伪装到位的钓鱼陷阱。员工稍有不慎点击链接、下载附件，就可能造成信息泄露、财务损失，给企业埋下巨大安全隐患。 很多企业管理者都面临这样的难题：员工防钓鱼意识不足、极易误入钓鱼陷阱，传统安全培训枯燥脱离实际，还没法用数据量化防护效果。为此，CACTER 反钓鱼演练系统（PhishSi

- **[梆梆安全发布《2026年Q1移动应用安全风险报告》：超八成APP存隐私违规，数据境外外发风险需高度警惕]()**
  - 梆梆安全发布《2026年Q1移动应用安全风险报告》。本报告基于梆梆安全移动应用监管平台在2026年一季度的威胁监测数据与深度安全分析成果，系统梳理当前国内移动应用面临的新型攻击技术演进与安全趋势变化，聚焦盗版仿冒、境外数据传输、高危漏洞、个人隐私违规等多个维度，为移动应用安全建设工作提供参考与实践指引。
当前，我国数字经济与实体经济融合持续深入，移动互联网已演进为支撑社会数字化转型的关键基础设施

*每日自动更新 · 来源: FreeBuf · 嘶吼 · 安全脉搏 · CISA · Dark Reading · Threatpost · Wired · CyberScoop · Cyble · KrebsOnSecurity*