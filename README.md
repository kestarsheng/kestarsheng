# 你好，我是刘宇珂(Yuke) 👋

## 🧭 关于我

- 🎓 河南大学 · 网络工程 2028 届本科（GPA 3.5/4.0，专业前 10%）
- 🔭 方向：AI 应用开发（Agent / RAG / MCP）· 全栈开发
- 💼 2026 夏完成一段 AI 智能体后端开发实习（企业智能体协同中台方向）
- 🌱 正在做：对话式数据分析智能体（NL2SQL），见下方
- 📫 邮箱：2410251355@henu.edu.cn
- ✍️ 博客：[掘金](https://juejin.cn/user/181873132458346)

## 🔥 项目

### [code-review-agent](https://github.com/kestarsheng/code-review-agent) · AI 代码审查 Agent（已部署在线 Demo）

X-Agent AI MCP Hackathon 2026 参赛作品。针对 AI 生成代码"无人把关"的问题：

- **三引擎交叉验证**：规则引擎（40 条跨语言规则 / 9 种语言，含 AI Hallucination 模式规则）+ AST 结构分析 + LLM 语义审查，双引擎命中自动加权置信度
- **10 个 MCP Tools + REST API 双形态**，支持 GitHub PR URL 直接审查
- 输出 **SARIF 2.1.0**，可直接接入 GitHub Code Scanning；**93 个 Unit Test** 覆盖
- 在线 Demo：https://code-review-agent-ashy-six.vercel.app

### [zhixiao-rag](https://github.com/kestarsheng/zhixiao-rag) · RAG 知识问答系统

面向制造业售后与客服的文档知识问答系统：

- **混合检索**：BGE-M3 稠密 + jieba BM25 稀疏 → RRF 融合 → BGE Reranker 精排
- **评测驱动**：基于 Ragas 构建 200+ 问答对回归基线，Context Relevancy 0.72 → 0.89
- 多格式解析（PDF / Word / PPT / TXT）+ 答案溯源（页码 / 章节 / 检索得分）

### [prompt-arsenal](https://github.com/kestarsheng/prompt-arsenal) · 提示词工程化工具链 ⭐3

[文档站](https://kestarsheng.github.io/prompt-arsenal)｜7 大场景「指令 + 变量 + 示例」三段式模板；递归扫描自动生成侧边栏 + Pagefind 中文搜索 + GitHub Actions push 即部署

### [prompt-arsenal-cli](https://github.com/kestarsheng/prompt-arsenal-cli) · 终端一键调用提示词模板【开发中】

配套 CLI，在终端和 coding agent 中直接调用提示词模板。

## 🚧 正在做

**对话式数据分析智能体（NL2SQL）**：自然语言进、SQL 与图表出。Schema 语义层检索解决多表选错问题，sqlglot 校验 + 报错回灌重试做自愈闭环，只读沙箱保证执行安全。完成后开源。

## 🧰 技术栈

**AI / LLM：** LangChain · LangGraph · MCP · A2A · Milvus · Ragas · RAG · Prompt Engineering
**后端：** Python · FastAPI · Java · Spring Boot · Spring Cloud Alibaba
**数据与基础设施：** MySQL · PostgreSQL · Redis · RabbitMQ · Docker · Nginx
**前端与工具：** Vue 3 · VitePress · Git · GitHub Actions

## 📚 学习中

- [Hugging Face Agents Course](https://github.com/kestarsheng/agents-course)

---

_持续把「学过」变成「做过」。_
