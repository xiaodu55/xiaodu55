# 杜凯峰 (xiaodu55)

**AI 应用 / Agent 方向 · 后端开发实习生** · 2028 届本科

- 🔭 正在做：Agent 平台工程化 —— RAG 全链路评测门禁、工具审批 exactly-once、多渠道 Agent 工作台
- 🌿 上游贡献：bytedance/deer-flow（字节开源 LangGraph 多智能体框架）**9 个 PR 全部合并** —— PII 脱敏中间件两期、gateway 租户隔离加固、sandbox 修复；单 PR 最长 **12 轮 review** 闭环
- 🛡️ 安全实践：负责任漏洞披露，获 **GHSA-6rv3 reporter credit**（HITL capability token 泄漏，medium）
- 📮 kfeng.du@outlook.com

---

## 开源项目

### [HFusionHub](https://github.com/xiaodu55/HFusionHub1) — 多租户 AI Agent 平台

Java（Spring Boot 3）+ Python（FastAPI）双语言分层：Java 独占 MySQL 写路径，Python 独占检索与 ReAct Agent。RAG 全链路（多路召回 / 证据门控 / 逐论断 [n] 引用溯源），**220 用例冻结评测套件接入 CI 阻断门禁**；工具审批一次性执行令牌（守卫 UPDATE）保证 exactly-once。测试资产：Java 697 / Python 1556 / 前端 101 + Playwright 73 E2E。

### 🔒 AgentHarbor — 自托管多渠道 AI Agent 工作台（私有仓库，可面试演示）

基于 Pi Agent Runtime 的工作台层：Web / Electron 与七类 IM 渠道统一接入、四账本可靠投递状态机、零网络沙箱与工具来源仲裁；20 例 Gold / Bad / Ambiguous 回放评测，误报 0%、危险动作拦截 100%。

---

## 技术栈

`Java / Spring Boot 3` · `Spring Cloud Alibaba` · `MyBatis Plus` · `Flyway` · `Python / FastAPI` · `TypeScript / Node.js / Electron / Vue 3` · `Redis（Lua / Redisson）` · `RocketMQ` · `MySQL / ShardingSphere` · `Milvus` · `Docker / Testcontainers` · `LangGraph` · `MCP`
