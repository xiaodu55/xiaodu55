<div align="center">
  <img src="assets/banner.svg" alt="AI Agent × Backend Engineering — AI applications & agent platforms" width="100%" />
</div>

<div align="center">
  <a href="#"><img alt="Java 17" src="https://img.shields.io/badge/Java-17-1F6FEB?logo=openjdk&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Spring Boot 3" src="https://img.shields.io/badge/Spring_Boot-3-1F6FEB?logo=spring&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="Python 3.11" src="https://img.shields.io/badge/Python-3.11-1F6FEB?logo=python&logoColor=white&style=flat-square" /></a>
  <a href="#"><img alt="FastAPI" src="https://img.shields.io/badge/FastAPI-✓-1F6FEB?logo=fastapi&logoColor=white&style=flat-square" /></a>
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

### 🧭 About Me

- **Backend developer focused on AI applications & Agent platforms** (undergraduate, class of 2028, available for internship)
- Currently building: Agent platform engineering — RAG evaluation gates, exactly-once tool approval, multi-channel agent workbench
- I believe in verifiable contributions: every number here matches the public record

### 🌿 Open-Source Contributions — 21 PRs Merged in 7 Upstream Repos

| Repository | Contribution | Result |
| --- | --- | --- |
| **bytedance/deer-flow** | PII redaction middleware (two slices: HMAC-keyed placeholders, 10+ data channels), gateway tenant-isolation hardening (P1), sandbox fixes | **9 PRs merged** · single PR closed a **12-round review loop** |
| **helsome/folio** | ConnectionStore concurrent-write clobbering, StreamEventHistory LRU ordering, bounded eval teardown | 5 PRs merged |
| **axonel/axonel** | Invited: Claude Code CLI backend, SecretRedactor | 2 PRs merged |
| **heymrun/heym** | Responsible disclosure of a HITL capability-token leak + atomic-claim race fix | **GHSA-6rv3 reporter credit** · 1 PR merged |
| Others | langgenius/dify · freeCodeCamp | 1 each |

### 🚀 Projects

**[HFusionHub](https://github.com/xiaodu55/HFusionHub1)** · Multi-tenant AI Agent platform — Java + Python split-tier

- Java owns the MySQL write path (transactions / multi-tenancy / billing ledger); Python owns retrieval & the ReAct agent — internal token + HMAC-signed contract, contract anchors enforced by CI
- Full RAG pipeline: hybrid retrieval (vector + BM25 + RRF) → evidence gating → per-claim [n] citations; **220-case frozen eval suite as a blocking CI gate** (recall@5 = 0.932)
- Exactly-once tool approval: one-time scoped execution token + guarded UPDATE; state machine via conditional UPDATE transitions, race-regression tested
- Tests: Java 697 / Python 1556 / frontend 101 + Playwright 73 E2E

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github-readme-stats.vercel.app/api/pin/?username=xiaodu55&amp;repo=HFusionHub1&amp;theme=github_dark&amp;hide_border=true" />
    <img src="https://github-readme-stats.vercel.app/api/pin/?username=xiaodu55&amp;repo=HFusionHub1&amp;hide_border=true" alt="HFusionHub1 repo card" />
  </picture>
</div>

**🔒 AgentHarbor** · Self-hosted multi-channel agent workbench (private repo, demo on request)

- Unified access across Web / Electron and 7 IM channels (Feishu, Telegram, QQ, DingTalk, WeChat, Discord, WhatsApp); four-ledger reliable delivery, zero-network sandbox, tool-source arbitration
- 20-case Gold / Bad / Ambiguous replay eval: 0% false positives, 100% dangerous-action interception

### 📮 Contact

`kfeng.du@outlook.com` — resume & project details on request
