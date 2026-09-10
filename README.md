赵宇哲 · Yuzhe Zhao

Java Backend · AI Agents · RAG

河南科技大学软件工程本科生，预计 2028 年毕业。围绕 Java 后端与 AI 应用做工程实践，关注检索增强生成、Agent 工作流、上下文与记忆，以及可复现的质量评测。

参与 Apache SeaTunnel 开源贡献，已合并 Milvus 与 Lance 连接器的参数校验、兼容性与回归测试改进。

目前关注 Java 后端 / AI Agent 方向的实习机会，欢迎交流项目与开源协作。

SuperBizAgent · AI Resume Analyzer · 开源 PR

代表项目

SuperBizAgent — RAG 问答与 AIOps Agent

基于 Spring Boot + Spring AI Alibaba，把知识库问答、工具调用与运维分析组织成可执行的 Agent 工作流。

RAG 问答：文档解析与切片、Milvus 检索、多轮对话、SSE 流式输出。

运维工作流：规划、执行、反馈与重规划，结合告警、文档及日志查询生成诊断报告。

记忆与上下文：会话历史、摘要与长期记忆，按用户隔离，并根据相关性与上下文预算选择内容。

质量评测：提供离线回归用例和运行时评测入口，检查检索证据、引用、无证据拒答及记忆隔离。

阅读工作流实现 · RAG 评测说明 · 运行时评测说明

AI Resume Analyzer — 智能简历分析

基于 FastAPI + Vue 3 + Qwen，完成 PDF 简历解析、结构化信息提取、岗位描述分析与匹配报告生成。

结合确定性规则、模型语义分析和结构校验，展示匹配依据与分项结果。

实现 Redis 可降级缓存，并提供 pytest / Vitest 测试、Docker 与 GitHub Actions 配置。

已合并的开源贡献

项目 / PR

贡献内容

合并日期

Apache SeaTunnel #12222

为 Lance Sink 增加非空白参数校验，保留默认值与可选语义，补充回归测试及中英文文档。

2026-09-10

Apache SeaTunnel #11504

将 Milvus Sink 的 batch_size 校验纳入声明式规则；拒绝负数，保留 0 的逐条刷新行为，并补充测试及中英文文档。

2026-07-21

参与开源时，我关注问题复现、向后兼容、回归测试，以及范围清晰、便于评审的改动。

常用技术

方向

技术与实践

后端

Java、Spring Boot、MySQL、Redis

AI 应用

Spring AI Alibaba、RAG、Agent 工作流、MCP、上下文与记忆

检索与数据

Milvus、文档解析与切片、检索质量评测

工程工具

Git、Docker、GitHub Actions、JUnit

其他项目实践

Python / FastAPI、Vue 3、pytest、Vitest

正在深入

RAG 与记忆的评测集、回归检查和结果分析。

Agent 工具执行、异常处理与状态一致性。

从问题复现到测试、文档和代码评审的完整开源贡献流程。

欢迎通过项目 Issue 交流实现思路、问题复现和协作机会。
