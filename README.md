# 原神拉表游戏数据库

当前推荐数据库为 **db-7.2.54-r1**。[查看本版说明](releases/db-7.2.54-r1/README.md)。

本仓为[原神拉表](https://github.com/Aiur-wzy/gs_ai_calculator)提供游戏资料的来源、版本与发布说明。首个正式数据库为 **db-7.2.50-r6**，首发配套 App **0.46.0-r19**，上游资料快照为 **7.2.50**。r6 沿用 r5 已核对的 SQLite 内容。

完整的数据库压缩包、校验值和签名配对以[数据库发行页](https://github.com/Aiur-wzy/gs_ai_calculator_db/releases)实际提供的附件为准。一般用户通过 App 小安装器或应用内下载获得配套数据库。仓库源码 ZIP 保存说明和清单，数据库 SQLite 作为发行附件提供。

**当前建议通过 App CLI 使用这些资料，配合 GPT-6.1 Sol 或能力更强的模型生成方案，再在 GUI 中看图、审核和寻找问题。**应用内原生 Agent 与 DeepSeek 的复杂任务表现仍不稳定。具体操作见[主仓 CLI 工作流](https://github.com/Aiur-wzy/gs_ai_calculator/blob/main/docs/cli-workflow.md)。

- [来源](docs/sources.md)和[资料声明](docs/data-status-and-disclaimer.md)
- [查询指南](docs/query-guide.md)、[数据结构](schemas/README.md)和[补充知识](knowledge/README.md)
- [维护与发布](docs/maintenance.md)、[发行清单](releases/README.md)和[更新记录](CHANGELOG.md)
- [正式 r6 版本说明](releases/db-7.2.50-r6/README.md)和[历史 r5 版本说明](releases/db-7.2.50-r5/README.md)

基础数据由上游公开资料整理，包含未上线、测试、废弃或状态未知的配置。仅供学习、研究和参考。本项目与游戏开发商及发行商无隶属关系。

数据库对530个角色、武器和套装实体记录上线状态：446个已上线、2个明确未上线、82个未知。任务采用未上线或未知实体前均需用户确认。程序代码的 MIT 许可不自动适用于游戏数据。
