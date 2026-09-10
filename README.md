
# 👋 你好，我是 ZYZ666-RGB

**软件工程本科生 | Java Backend × AI Agent / RAG**

我目前主要关注 **Java 后端工程与 AI 应用开发**，正在持续学习和实践 Agent、RAG、Memory、Knowledge Graph 等方向。

我喜欢把 AI 能力真正落到工程系统中，而不只是简单调用模型 API：  
从 **知识库构建、混合检索、Agent Planning、Tool Calling、长期记忆，到自动化评测 Harness**，都在持续实践和完善。

目前也在积极参与开源社区，希望通过真实 Issue / PR 提升自己的工程能力。

> 🎯 **Looking for:** Java Backend / AI Agent Internship  
> ⏱️ **Availability:** 6+ months · Available within one week

---

## 🎯 重点

- 🤖 **AI Agent 工程**：Planning、ReAct、Tool Calling、Dynamic DAG、Multi-Agent
- 📚 **RAG 系统**：Query Rewrite、BM25 + Dense Retrieval、RRF、Rerank、Milvus / Elasticsearch
- 🧠 **Agent Memory**：短期记忆、长期记忆、偏好记忆、Graph Memory
- 🕸️ **Knowledge Graph**：Neo4j、实体关系抽取、Graph-enhanced Retrieval
- ☕ **Java Backend**：Spring Boot、MySQL、Redis、Kafka、RabbitMQ
- 📊 **Evaluation**：Recall@K、MRR、nDCG、HitRate、Agent / RAG Evaluation Harness
- 🌱 **Open Source**：Issue 复现、Root Cause 分析、最小改动、测试覆盖、PR Review

---

## 🚀 项目

### 🤖 AGI Assistant — Java AI Agent Framework

一个基于 Java 构建的 AI Agent 学习与实践项目，围绕完整 Agent Runtime 进行设计。

**主要能力：**

`LLM Chat` · `RAG` · `Tool Agent` · `ReAct` · `Memory` · `Evaluation Harness`

核心设计包括：

- 使用 **Planner → Dynamic DAG → GraphRuntime** 实现复杂任务规划与执行
- 支持 **ReAct Loop + Function Calling + Tool Runtime**
- 构建短期记忆、长期记忆与 **Graph Memory**
- 使用 **Milvus + Elasticsearch + Neo4j** 实现 Dense / BM25 / KG 三路检索
- 基于 **RRF** 完成多路检索结果融合
- 支持 Query Rewrite / Multi Query / Context Compression
- 设计 Agent / RAG 自动化评测 Harness

**Tech Stack**

`Java` `Spring Boot` `LLM` `Milvus` `Elasticsearch` `Neo4j` `PostgreSQL` `Kafka` `Docker`

---

### 🛠️ SuperBizAgent — AI Agent 运维助手

面向运维场景设计的智能 Agent 系统，将知识库问答与 AIOps Agent 结合。

核心能力：

- 基于 **Spring AI Alibaba + Qwen** 构建 AI Agent
- 使用 **Milvus** 实现企业知识库向量检索
- 支持多轮对话与 SSE Streaming
- 使用 **Planner → Executor → Replanner** 完成复杂运维任务
- 支持告警分析、日志查询、故障诊断与报告生成
- 设计 Knowledge Agent / Conversation Agent / Ops Agent 多 Agent 协作

**Tech Stack**

`Java` `Spring Boot` `Spring AI Alibaba` `Milvus` `MinIO` `Docker` `SSE`

---

### 📚 AI Knowledge Base — Hybrid RAG System

一个面向技术知识库场景设计的 RAG 检索问答系统。

完整链路：

**Document Upload → Parse → Chunk → Embedding → Index → Retrieval → Rerank → LLM**

主要设计：

- 支持文件分片上传与断点续传
- Kafka 异步完成文档解析和索引构建
- 使用 Header-aware + Recursive + Code-aware Chunking
- 使用 **Elasticsearch BM25 + Dense Vector** 混合检索
- 使用 **RRF** 融合多路召回结果
- 使用 WebSocket 实现流式 AI 问答
- 持续探索 Neo4j Knowledge Graph 与 Agent Memory

**Tech Stack**

`Java` `Spring Boot` `Elasticsearch` `MySQL` `Redis` `Kafka` `MinIO` `Docker`

---

## 🌱 开源

我正在持续参与 **Java / AI / Developer Infrastructure** 相关开源项目。

近期主要关注：

**Lark / Feishu · Spring AI · RAG · Agent · SDK / CLI**

相比单纯提交代码，我更关注完整的工程问题解决过程：

**Reproduce → Root Cause → Design → Minimal Fix → Regression Test → PR Review**

对于一个问题，我通常会先复现并定位根因，再尽可能保持改动范围足够小，同时补充测试避免 Regression。

目前已有开源 PR 被项目维护者合并，也有多个 Issue / PR 正在 Review 中。

> 希望通过真实的开源协作，持续提升代码质量、工程设计和大型项目协作能力。

---

## 🔬 当前正在研究

```text
AI Agent
├── Planning
│   ├── Planner / Executor
│   ├── Dynamic DAG
│   └── Graph Runtime
│
├── ReAct
│   ├── Reasoning
│   ├── Tool Calling
│   └── Observation Loop
│
├── Memory
│   ├── Short-Term Memory
│   ├── Long-Term Memory
│   └── Graph Memory
│
├── RAG
│   ├── Query Rewrite
│   ├── BM25 Retrieval
│   ├── Dense Retrieval
│   ├── RRF Fusion
│   └── Rerank
│
└── Evaluation
    ├── Recall@K
    ├── MRR
    ├── nDCG
    └── Agent Harness
````

---

## 🛠️ 技术栈

### Languages

![Java](https://img.shields.io/badge/Java-Backend-orange?logo=openjdk)
![Go](https://img.shields.io/badge/Go-Learning-00ADD8?logo=go)
![Python](https://img.shields.io/badge/Python-AI-3776AB?logo=python)

### Backend

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?logo=springboot\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?logo=redis\&logoColor=white)
![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka)

### AI / RAG

![Spring AI](https://img.shields.io/badge/Spring_AI-Agent-green)
![Milvus](https://img.shields.io/badge/Milvus-Vector_DB-blue)
![Elasticsearch](https://img.shields.io/badge/Elasticsearch-BM25-yellow?logo=elasticsearch)
![Neo4j](https://img.shields.io/badge/Neo4j-Knowledge_Graph-4581C3?logo=neo4j)

### Engineering

![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker\&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?logo=git\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?logo=linux\&logoColor=black)

---

## 📈 GitHub

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=ZYZ666-RGB\&show_icons=true\&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ZYZ666-RGB\&layout=compact\&hide_border=true)

---

## 📫 联系方式

* GitHub：[@ZYZ666-RGB](https://github.com/ZYZ666-RGB)
* Email：你的邮箱

```

我特别给你加了一个原 README 没有的 **「当前正在研究」Agent 技术树**。这个对于你比普通的“MySQL / Redis / Docker”技术栈更加重要，因为你的目标不是让别人只觉得你是一个普通 Java 后端学生，而是形成一个非常明确的标签：

> **Java 后端基础 + Agent/RAG 工程实践 + 开源贡献**

另外我建议你主页最上方不要写得像截图里那个人一样“我是一名软件工程师”，你目前更适合写 **「软件工程本科生 | Java Backend × AI Agent / RAG」**，这样既真实，又不会降低技术含量。

等你的几个正在 Review 的开源 PR 后续继续合并之后，**「开源」这一块还可以升级成截图里那种“Merged Contributions”形式，把仓库名、PR #、解决的问题全部直接列出来**。这会成为你 GitHub 首页含金量最高的一块。
```
