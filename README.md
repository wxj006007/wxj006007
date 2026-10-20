<h1 align="center">Hi, I'm wxj006007 👋</h1>

<p align="center">
  <strong>Python Backend · AI Applications · Agent Systems</strong><br>
  2028 届 · 开发者<br>
  寻找 Agent 开发 / 后端开发实习
</p>

<p align="center">
  <a href="#selected-projects">精选项目</a> ·
  <a href="#tech-stack">技术栈</a>
</p>

---

### 关于我

我是 wxj006007，关注 **Python 后端与 AI 应用开发**，预计 **2028 年毕业**，正在寻找 **Agent 开发 / 后端开发实习**。

我负责 AI Meeting、Cloud Agent 和 AI Sidebar 三个项目的全部模块开发，实践覆盖后端 API、Agent 编排、数据存储与前端交互。我关注如何把模型能力接入具体的使用场景，并持续打磨服务的可靠性和使用体验。

- **后端工程**：异步 API、鉴权、缓存、任务队列，以及有状态业务的并发与一致性。
- **AI / Agent**：多智能体工作流、工具调用、上下文组织与记忆管理。
- **产品实现**：流式对话、实时语音、浏览器扩展与可运行的交互界面。

<a id="selected-projects"></a>

### 精选项目

#### 🎙️ [AI Meeting · AI 模拟面试平台](https://github.com/wxj006007/ai-meeting)

围绕「简历上传 → AI 出题 → 语音 / 文字作答 → 评分与追问 → 复盘报告」构建面试练习流程。

**个人职责：**负责项目全流程开发，涵盖后端业务、前端 Demo、语音与 AI 服务集成，以及测试和容器配置。

- **交互链路**：提供面试、AI 会话与智能体会话功能，接入实时语音转写、语音合成和 SSE 流式响应。
- **状态与并发**：通过 Redis 状态机、Lua CAS、幂等控制与题级锁，处理重复提交和面试进度冲突。
- **工程配套**：包含前端 Demo、数据库迁移、自动化测试与 Docker Compose 启动配置。

`Python` `FastAPI` `MySQL` `MongoDB` `Redis` `WebSocket`

#### 🧠 [Cloud Agent · 多智能体研究与问答](https://github.com/wxj006007/cloud_agent)

面向云平台场景，将智能体编排、工具调用与多层记忆整合到研究问答流程。

**个人职责：**负责智能体工作流、MCP 工具集成、记忆与知识存储、后端接口及前端聊天界面的开发。

- **智能体编排**：使用 LangGraph 组织工作流，通过 MCP 接入工具。
- **记忆与知识**：Redis 承载短期记忆，Milvus 提供长期记忆与语义缓存，Neo4j 存储知识图谱。
- **使用入口**：提供 FastAPI 流式接口、Vue 3 聊天界面与 CLI 查询方式。

`Python` `LangGraph` `MCP` `Milvus` `Neo4j` `Vue 3`

#### 🌐 [AI Sidebar · 浏览器 AI 助手](https://github.com/wxj006007/ai-sidebar-extension)

把网页阅读与 AI 对话结合起来，支持选中文字提问、附加页面正文和一键总结。

**个人职责：**负责扩展全部模块开发，涵盖网页内容提取、上下文组织、模型接入、会话管理与侧边栏交互。

- **上下文处理**：提取网页正文、过滤页面噪音，并为选中片段附加周边内容。
- **对话体验**：支持流式输出、多会话管理、历史持久化与多轮上下文窗口。
- **模型接入**：兼容 OpenAI 格式的 API，支持模型切换与独立密钥配置。

`TypeScript` `React` `Vite` `Tailwind CSS` `Chrome Extension MV3`

#### ⚙️ [FastAPI Task API · 异步任务管理服务](https://github.com/wxj006007/fastapi-task-api)

用于后端工程实践的任务管理 API，覆盖 JWT 鉴权、任务 CRUD、分页筛选、Redis 缓存与 Celery 异步 CSV 导出，并提供测试与 Docker Compose 配置。

`Python` `FastAPI` `PostgreSQL` `Redis` `Celery` `Docker`

<a id="tech-stack"></a>

### 项目中使用的技术

| 方向 | 技术与工具 |
| --- | --- |
| 后端与接口 | Python · FastAPI · Pydantic · SQLAlchemy · SSE · WebSocket |
| AI 与智能体 | LangGraph · MCP · 模型 API 集成 · 上下文与记忆管理 |
| 数据与任务 | MySQL · PostgreSQL · MongoDB · Redis · Milvus · Neo4j · Celery |
| 前端与扩展 | TypeScript · React · Vue 3 · Vite · Tailwind CSS · Chrome Extension |
| 工程工具 | Git · Docker Compose · pytest · Ruff · Alembic · uv |

---

### 实习与联系

正在寻找 **Agent 开发 / 后端开发实习**，希望参与智能体应用、AI 工具与后端服务的开发。

- **毕业时间：**2028 年
- **联系方式：**GitHub 个人资料中展示的邮箱

欢迎联系交流岗位机会，也欢迎通过项目仓库的 Issues 讨论实现细节与改进建议。
