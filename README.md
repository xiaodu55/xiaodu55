<div align="center">
  <img src="assets/banner.svg" alt="杜凯峰 · AI 应用 / Agent 方向 · 后端开发实习" width="100%" />
</div>

<div align="center">
  <a href="#"><img alt="Java 17" src="https://img.shields.io/badge/Java-17-1F6FEB?logo=openjdk&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Spring Boot 3" src="https://img.shields.io/badge/Spring_Boot-3-1F6FEB?logo=spring&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Python 3.11" src="https://img.shields.io/badge/Python-3.11-1F6FEB?logo=python&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-⭐-1F6FEB?logo=fastapi&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="TypeScript" src="https://img.shields.io/badge/TypeScript-✓-1F6FEB?logo=typescript&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Node.js" src="https://img.shields.io/badge/Node.js-✓-1F6FEB?logo=nodedotjs&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Vue 3" src="https://img.shields.io/badge/Vue-3-1F6FEB?logo=vuedotjs&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="MySQL" src="https://img.shields.io/badge/MySQL-✓-1F6FEB?logo=mysql&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Redis" src="https://img.shields.io/badge/Redis-✓-1F6FEB?logo=redis&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="RocketMQ" src="https://img.shields.io/badge/RocketMQ-5-1F6FEB?logo=apacherocketmq&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Milvus" src="https://img.shields.io/badge/Milvus-✓-1F6FEB?logo=milvus&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Docker" src="https://img.shields.io/badge/Docker-✓-1F6FEB?logo=docker&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="LangGraph" src="https://img.shields.io/badge/LangGraph-✓-1F6FEB?logo=langgraph&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="MCP" src="https://img.shields.io/badge/MCP-✓-1F6FEB?style=flat-square" /></a>
</div>

---

### 🧭 关于我

- **AI 应用 / Agent 方向 · 后端开发实习生**（2028 届本科，可日常实习）
- 正在做：Agent 平台工程化 —— RAG 全链路评测门禁、工具审批 exactly-once、多渠道 Agent 工作台
- 相信可验证的贡献：简历与主页上的每一条数字，都能在公开记录里对上

### 🌿 上游开源贡献 —— 21 PRs Merged in 7 upstream repos

| 仓库 | 贡献内容 | 结果 |
| --- | --- | --- |
| **bytedance/deer-flow** | PII 脱敏中间件两期（HMAC 键控占位符 / 10+ 数据通道）、gateway 租户隔离加固（P1）、sandbox 修复 | **9 PRs merged** · 单 PR **12 轮 review** 闭环 |
| **helsome/folio** | ConnectionStore 并发写覆盖、StreamEventHistory LRU 失序、eval 超时有界收尾 | 5 PRs merged |
| **axonel/axonel** | 受邀贡献：Claude Code CLI backend、SecretRedactor | 2 PRs merged |
| **heymrun/heym** | HITL capability token 泄漏负责任披露 + 原子领取竞态修复 | **GHSA-6rv3 reporter credit** · 1 PR merged |
| 其他 | langgenius/dify · freeCodeCamp | 各 1 |

### 🚀 项目

**[HFusionHub](https://github.com/xiaodu55/HFusionHub1)** · 多租户 AI Agent 平台 —— Java + Python 双语言分层

- Java 独占 MySQL 写路径（事务 / 多租户 / 计费账本），Python 独占检索与 ReAct Agent；内部令牌 + HMAC 签名契约，CI 静态校验
- RAG 全链路：多路召回（向量 + BM25 + RRF）→ 证据门控 → 逐论断 [n] 引用溯源；**220 用例冻结评测套件接入 CI 阻断门禁**（recall@5 = 0.932）
- 工具审批 exactly-once：一次性 scoped 执行令牌 + 守卫 UPDATE；任务状态机条件 UPDATE 迁移，竞态回归测试锁定
- 测试资产：Java 697 / Python 1556 / 前端 101 + Playwright 73 E2E

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=xiaodu55&amp;repo=HFusionHub1&amp;theme=github_dark&amp;hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=xiaodu55&amp;repo=HFusionHub1&amp;hide_border=true" alt="HFusionHub1 repo card" />
  </picture>
</div>

**🔒 AgentHarbor** · 自托管多渠道 AI Agent 工作台（私有仓库，可面试演示）

- Web / Electron 与飞书 / Telegram / QQ / 钉钉 / 微信 / Discord / WhatsApp 七类渠道统一接入；四账本可靠投递状态机、零网络沙箱、工具来源仲裁
- 20 例 Gold / Bad / Ambiguous 回放评测：误报 0%、危险动作拦截 100%

### 📮 联系

`kfeng.du@outlook.com` · 简历与项目详情欢迎邮件交流
