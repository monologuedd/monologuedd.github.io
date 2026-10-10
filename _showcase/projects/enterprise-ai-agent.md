---
show: true
width: 6
date: 2024-12-01 00:00:00 +0800
group: Selected Projects
---

<div class="p-4">
    <h5><i class="fas fa-project-diagram text-muted mr-1"></i> AI Agent 智能体平台 (Enterprise AI Agent Platform)</h5>
    <div class="small text-muted mb-2">Enterprise AI Agent Platform with RAG and MCP</div>
    <div class="mb-3">
        <span class="badge badge-light border mr-1 mb-1">Java</span>
        <span class="badge badge-light border mr-1 mb-1">Spring Boot 3</span>
        <span class="badge badge-light border mr-1 mb-1">Spring AI</span>
        <span class="badge badge-light border mr-1 mb-1">MySQL</span>
        <span class="badge badge-light border mr-1 mb-1">Redis</span>
        <span class="badge badge-light border mr-1 mb-1">Kryo</span>
        <span class="badge badge-light border mr-1 mb-1">PostgreSQL</span>
        <span class="badge badge-light border mr-1 mb-1">PGvector</span>
        <span class="badge badge-light border mr-1 mb-1">SSE</span>
        <span class="badge badge-light border mr-1 mb-1">CompletableFuture</span>
        <span class="badge badge-light border mr-1 mb-1">MCP</span>
        <span class="badge badge-light border mr-1 mb-1">Ollama</span>
    </div>
    <p class="small mb-2"><strong>TL;DR:</strong> 构建支持多模型切换、持久化对话记忆、RAG 知识检索及自主工具调用的企业级 AI Agent 平台。</p>
    <hr />
    <ul class="list-unstyled small mb-0">
        <li class="mb-2">
            <strong>多模型接入与记忆管理：</strong>基于 Spring AI 统一接入通义、Ollama 等 5 种 AI 大模型，通过统一调用接口支持灵活切换；结合 ChatMemory、Advisor、MySQL、Redis 与 Kryo 实现对话记忆持久化，解决服务重启后的上下文丢失问题。
        </li>
        <li class="mb-2">
            <strong>RAG 知识库与工具调用：</strong>构建完整的知识检索流程，涵盖文档 ETL、PGvector 向量存储、元信息标注、多查询扩展及查询重写；通过 Spring AI 工具调用实现联网搜索、网页抓取、资源下载和 PDF 生成。
        </li>
        <li class="mb-0">
            <strong>自主规划与 MCP 服务：</strong>参考 OpenManus 设计分层智能体架构，支持任务自主规划与分步执行，并通过步骤限制、状态管理和循环检测增强运行稳定性；开发支持 Stdio 与 SSE 双传输模式的图片搜索 MCP 服务，提升能力复用性。
        </li>
    </ul>
</div>
