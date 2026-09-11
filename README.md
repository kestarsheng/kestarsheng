# 你好，我是刘宇珂(Yuke) 👋


## 🧭 关于我

- 🎓 河南大学 · 网络工程（GPA 3.5/4.0，专业前 10%）
- 🔭 专注方向：AI Agent 应用开发、RAG 检索增强与评估、Prompt Engineering
- 🌱 正在深入：Agent 可观测性与根因定位、MCP / A2A 协议工程化
- 📫 邮箱：2410251355@henu.edu.cn
- 🤝 活跃参与开源
  
## 🔥 项目

### [huizhitong-agent](https://github.com/kestarsheng/huizhitong-agent) · 智能体协同中台

面向企业运营、客服与销售部门的智能体协同中台：Java 微服务承载业务与治理，Python 承载 LangGraph 编排、RAG 与 MCP，Vue 3 提供控制台。

- **LangGraph 多智能体编排**：意图分类 → 任务规划 → 并行扇出 → 结果校验 → 答案生成，SSE 流式输出节点执行进度
- **A2A 跨智能体协同**：入口智能体识别意图，LLM / 规则路由并行转发库存、知识、工单专业智能体后协同汇总
- **RAG 混合检索**：BGE-M3 稠密 + 稀疏向量 → RRF 融合 → BGE-reranker-large 重排
- **MCP 工具接入**：库存 / 工单查询统一封装，支持注册、目录刷新与健康检查
- **工具授权 RBAC + 多租户隔离**：未授权工具对话中返回 FORBIDDEN
- **JWT + 网关统一鉴权**：Gateway 统一校验透传，绕过网关直连同样被拦截
- **双模型网关**：DeepSeek 主 + 通义千问降级，异常自动切换
- **调用审计**：RabbitMQ 异步落库 MySQL，MQ 故障自动降级直写

### [code-review-agent](https://github.com/kestarsheng/code-review-agent) · AI Code Review Agent

MCP hackathon 2026 参赛作品，把代码质量审查做成交互式服务：

- 基于 MCP 协议对接 IDE / CI，做增量代码审查
- 可配置规则与严重级别，输出结构化审查意见
- Python 实现，聚焦 Agent 与工具协议（MCP）的工程化落地

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

## 📚 学习中

- [Hugging Face Agents Course](https://github.com/kestarsheng/agents-course) · Agent 开发系统课程


---

_持续把「学过」变成「做过」。_
