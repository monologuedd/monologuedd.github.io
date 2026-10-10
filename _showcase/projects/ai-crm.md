---
show: true
width: 6
date: 2026-08-01 00:00:00 +0800
group: Selected Projects
---

<div class="p-4">
    <h5><i class="fas fa-robot text-muted mr-1"></i> AI CRM (AI-Powered CRM Platform)</h5>
    <div class="small text-muted mb-2">AI CRM — Enterprise AI Collaboration Platform</div>
    <div class="mb-3">
        <span class="badge badge-light border mr-1 mb-1">Java 21</span>
        <span class="badge badge-light border mr-1 mb-1">Spring Boot 3.3</span>
        <span class="badge badge-light border mr-1 mb-1">Spring AI 1.0</span>
        <span class="badge badge-light border mr-1 mb-1">MyBatis-Plus</span>
        <span class="badge badge-light border mr-1 mb-1">PostgreSQL 17</span>
        <span class="badge badge-light border mr-1 mb-1">Redis</span>
        <span class="badge badge-light border mr-1 mb-1">MinIO</span>
        <span class="badge badge-light border mr-1 mb-1">Vue 3</span>
        <span class="badge badge-light border mr-1 mb-1">TypeScript</span>
        <span class="badge badge-light border mr-1 mb-1">Element Plus</span>
        <span class="badge badge-light border mr-1 mb-1">Pinia</span>
        <span class="badge badge-light border mr-1 mb-1">Tailwind CSS</span>
        <span class="badge badge-light border mr-1 mb-1">Vite</span>
        <span class="badge badge-light border mr-1 mb-1">WeKnora</span>
    </div>
    <p class="small mb-2"><strong>TL;DR:</strong> 构建融合 CRM 业务、企业知识库与 AI 对话能力的智能工作平台，通过自然语言交互实现客户管理、任务创建、知识问答及邮件草稿生成。</p>
    <hr />
    <ul class="list-unstyled small mb-0">
        <li class="mb-2">
            <strong>AI 工具调用与业务集成：</strong>基于 Spring AI 将客户、联系人、任务、日程、知识库及招聘等业务能力封装为工具，并按业务技能隔离工具组，实现多个业务场景下的统一 AI 交互与精准工具调用。
        </li>
        <li class="mb-2">
            <strong>上下文感知与企业级 RAG：</strong>设计业务对象绑定会话机制，将客户、候选人、产品等对象信息注入提示词，降低多轮对话中的指代歧义；集成 WeKnora，实现文档解析、异步知识同步、语义检索及带来源引用的知识问答。
        </li>
        <li class="mb-0">
            <strong>权限控制与多模型架构：</strong>构建兼容多个主流模型供应商的 Provider 抽象层，支持自定义 API 地址与模型能力识别；复用 CRM 角色、菜单及数据范围权限，在数据进入模型前执行权限过滤，并通过人工审核机制控制邮件发送风险。
        </li>
    </ul>
</div>
