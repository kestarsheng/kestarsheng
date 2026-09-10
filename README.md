# 你好，我是刘宇珂(Yuke) 👋


## 🧭 关于我

- 🎓 河南大学 · 网络工程（GPA 3.5/4.0，专业前 10%）
- 🔭 专注方向：AI Agent 应用开发、RAG 检索增强与评估、Prompt Engineering
- 🌱 正在深入：Agent 可观测性与根因定位、MCP / A2A 协议工程化
- 📫 邮箱：2410251355@henu.edu.cn

## 🔥 项目

### [huizhitong-agent](https://github.com/kestarsheng/huizhitong-agent) · 智能体协同中台

基于 Spring Cloud Alibaba 微服务 + LangGraph 编排的多智能体协同平台：

- 多智能体流程编排与状态机（PostgreSQL Checkpoint 持久化，支持任务中断恢复）
- MCP 标准化工具接入，工具复用率提升约 40%
- A2A 跨智能体协同：客服 / 库存 / 知识三类 Agent 任务转派
- 可观测层：RabbitMQ 异步审计日志 + FastAPI SSE 实时进度推送
- 模型网关：DeepSeek 主 + Qwen 降级，Sentinel 限流熔断

### [zhixiao-rag](https://github.com/kestarsheng/zhixiao-rag) · RAG 知识问答系统

面向制造业售后与客服的文档知识问答系统：

- 混合检索：Milvus 向量检索 + BM25 关键词 + Rerank 重排序
- 基于 Ragas 的离线评估体系，以 Context Relevancy / Faithfulness 指标驱动迭代
- 多格式文档解析（PDF / Word / PPT / TXT）+ 答案溯源

### [prompt-arsenal](https://github.com/kestarsheng/prompt-arsenal) · 个人 AI 提示词库

高频开发场景的结构化提示词模板库：VitePress 文档站 + GitHub Actions CI/CD + 侧边栏自动生成脚本。

### [prompt-arsenal-cli](https://github.com/kestarsheng/prompt-arsenal-cli) · 终端一键调用提示词模板

配套 CLI 工具，在终端和 coding agent 中一键调用提示词模板。【开发中】

## 🧰 技术栈

**AI / LLM：** LangChain · LangGraph · MCP · Milvus · Ragas · RAG

**后端：** Java · Spring Boot · Spring Cloud · Python · FastAPI

**数据与基础设施：** MySQL · PostgreSQL · Redis · RabbitMQ · Docker · Nginx

**前端与工具：** Vue 3 · VitePress · Git · GitHub Actions


---

_持续把「学过」变成「做过」。_
