# Xiangguo Zhang · 章向国

I build LLM agents and applications, fine-tune and serve the models myself, and publish the runs that did not work.

从 Agent 应用到微调、推理服务，这条链我自己跑通；跑砸的实验，原样公开。

**Open to:** AI agent & LLM application engineering · backend & distributed systems · data engineering & analytics<br>
**校招方向：** AI Agent 与大模型应用工程 · 后端与分布式系统 · 数据工程与分析

## Selected work · 精选项目

| Project · 项目 | What I built · 我做了什么 | Evidence · 实测结果 |
| --- | --- | --- |
| [frontier-forge](https://github.com/LucisZhang/frontier-forge) | 4B post-training → vLLM serving → C++20 gateway.<br>4B 模型后训练 → vLLM 推理服务 → C++20 网关。 | **66.35% → 99.05%**; **$35.68** total.<br>**66.35% → 99.05%**；全程实测花费 **$35.68**。 |
| [release-guardian](https://github.com/LucisZhang/release-guardian) | LangGraph agent release gate with durable human approval.<br>LangGraph Agent 发布门禁，人工审批状态可持久化恢复。 | **132** funded live runs; **8/8** aggregate gates; **30/44** strict residual.<br>**132** 次付费在线运行；**8/8** 聚合门禁通过；严格口径残差 **30/44**。 |
| [triage-router](https://github.com/LucisZhang/triage-router) | Confidence cascade routes complaints to the cheapest capable tier.<br>用置信度级联，把投诉分给能处理它的最低成本层级。 | **−$120.58 / 1k calls**.<br>**−$120.58 / 1k 次调用**。 |
| [exactly-once-drills](https://github.com/LucisZhang/exactly-once-drills) | Failure injection and recovery checks for CDC / Kafka → Flink → Iceberg.<br>为 CDC / Kafka → Flink → Iceberg 管道做故障注入与恢复对账。 | **10** failure classes; **0** snapshot diffs.<br>**10** 类故障；恢复后快照差异为 **0**。 |
| [privacy-preflight](https://github.com/LucisZhang/privacy-preflight) | Browser-local redaction workbench with English and Simplified Chinese OCR.<br>浏览器本地脱敏工作台，支持英文和简体中文 OCR。 | OCR **18/19** expected-value hits; **0** false positives.<br>OCR 预期值命中 **18/19**；误报 **0** 项。 |
| [crossover-study](https://github.com/LucisZhang/crossover-study) | Pre-registered comparison of popularity and personalization across high- and low-churn datasets.<br>预先登记检验，对比高、低目录换血数据上的热门榜与个性化。 | **41%** catalog churn; **n\*=∞ vs n\*=20**.<br>目录换血率 **41%**；**n\*=∞ 对 n\*=20**。 |

Measurements are scoped to the linked artifacts and their recorded test conditions. The portfolio keeps the receipts, boundaries, and failed runs visible.<br>
所有数字都只适用于链接中的证据与已记录测试条件；作品集同时保留数据来源、结论边界和失败实验。

[作品集 · Portfolio](https://xiangguozhang.com) · [Email](mailto:HsiangKuoChang@outlook.com)
