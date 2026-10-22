### Hi, I'm Light-Towers

10 年后端与数据工程经验（Java → 大数据 → AI 平台），现专注 AI Agent 平台与工程化落地。

我相信「已实现 ≠ 已接线」——把系统边界状态讲清楚，比宣称「生产级」更有价值。

#### 在维护的项目

| 项目 | 一句话 |
|---|---|
| [agent-platform](https://github.com/Light-Towers/agent-platform) | 统一 Agent 平台：LangGraph Supervisor 编排 + 搜索 / RAG / Text-to-SQL / MCP 四链路；uv workspace monorepo；CI 评测门禁；README 含能力现状四档交底 |
| [handle_video](https://github.com/Light-Towers/handle_video) | GPU 视频超分工具集（Real-ESRGAN + 双三次）：断点续传、音视频合并、编码兼容优化 |

#### 历史项目

| 项目 | 说明 |
|---|---|
| [reliable-agent](https://github.com/Light-Towers/reliable-agent) | 2026-08 的框架无关可靠性原语（tracing / guardrails / 检索质量指标 / 多模型客户端 / 工具注册与隔离调用）。**已停止独立维护**——能力并入 `agent-platform` 的 `packages/agent-core`，该包此后持续演进（60+ 次提交）；本仓保留为历史快照。 |

#### 技术栈

Python / Java · LangGraph / DeepAgents · RAG（pgvector + BM25 + RRF）· Text-to-SQL · MCP
PostgreSQL / Milvus / Qdrant / Elasticsearch · Docker / K8s / CI 门禁 · OTel / Langfuse

> 仓库 README 里的「能力现状四档交底」是有意为之：哪些默认开、哪些 opt-in、哪些还是骨架，写在明处。
