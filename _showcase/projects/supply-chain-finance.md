---
show: true
width: 6
date: 2025-06-01 00:00:00 +0800
group: Selected Projects
---

<div class="p-4">
    <h5><i class="fas fa-coins text-muted mr-1"></i> 供应链金融系统 (Supply Chain Finance System)</h5>
    <div class="small text-muted mb-2">Supply Chain Finance Management System</div>
    <div class="mb-3">
        <span class="badge badge-light border mr-1 mb-1">Java</span>
        <span class="badge badge-light border mr-1 mb-1">Spring Boot</span>
        <span class="badge badge-light border mr-1 mb-1">Spring Cloud Alibaba</span>
        <span class="badge badge-light border mr-1 mb-1">Nacos</span>
        <span class="badge badge-light border mr-1 mb-1">Seata</span>
        <span class="badge badge-light border mr-1 mb-1">Sentinel</span>
        <span class="badge badge-light border mr-1 mb-1">Redis</span>
        <span class="badge badge-light border mr-1 mb-1">Redisson</span>
        <span class="badge badge-light border mr-1 mb-1">RocketMQ</span>
        <span class="badge badge-light border mr-1 mb-1">MySQL</span>
        <span class="badge badge-light border mr-1 mb-1">Flowable</span>
        <span class="badge badge-light border mr-1 mb-1">Docker</span>
        <span class="badge badge-light border mr-1 mb-1">Vue 3</span>
        <span class="badge badge-light border mr-1 mb-1">Element Plus</span>
        <span class="badge badge-light border mr-1 mb-1">Python</span>
    </div>
    <p class="small mb-2"><strong>TL;DR:</strong> 从零设计并开发基于微服务架构的供应链金融管理系统，覆盖采购、销售、支付、库存及审批等核心业务流程。</p>
    <hr />
    <ul class="list-unstyled small mb-0">
        <li class="mb-2">
            <strong>微服务架构与分布式事务：</strong>负责系统从架构设计到交付上线的全流程研发，采用 Spring Cloud Alibaba 构建微服务体系，并使用 Seata AT 模式管理跨服务事务，保障采购订单与库存操作的数据一致性。
        </li>
        <li class="mb-2">
            <strong>高并发与系统稳定性：</strong>基于 Redis Lua 脚本实现库存查询与扣减的原子操作，降低超卖风险；结合 Sentinel 熔断降级、Redisson 分布式锁及幂等 Token，提升核心业务链路的稳定性与并发处理能力。
        </li>
        <li class="mb-0">
            <strong>异步处理与流程自动化：</strong>通过 RocketMQ 实现支付后订单、仓储及会员业务的异步解耦，使用 Flowable 实现多级审批流程，并开发 Python 数据清洗和运营报表生成工具。
        </li>
    </ul>
</div>
