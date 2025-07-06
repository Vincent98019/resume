<script setup>

</script>

<template>
  <div class="container">
    <div class="title">项目经历</div>
    <hr/>
    <div class="project">
      <div class="project-info">
        <div class="name">智慧园区项目</div>
        <div class="date">2021年5月 至今</div>
      </div>
      <div class="position">Java后端开发</div>
      <div class="item">
        <span>项目架构：</span>
        SpringCloud + MyBatis + Redis + Oracle + MQTT + RabbitMQ
      </div>
      <div class="item">
        <span>项目描述：</span>
        整套系统涉及多个客户端，中心管理端，园区管理端，企业管理端，个人端等。
        目前多个地区园区（如小程序：饭粒美好家）使用该项目或基于该项目定制化开发，推动园区、企业、人才的协同，提高企业智能化、统一化、数字化等先进发展。
      </div>
      <div class="item">
        <span>主要职责：</span>
        <ul class="content">
          <li>
            参与项目第二阶段的业务模块拆分和代码重构，成功将单体应用转化为微服务架构。
          </li>
          <li>
            负责商城模块开发，采用通用小型商城解决方案，集成微信支付，使用Redis结合LUA脚本实现库存扣减与秒杀等高并发场景的原子操作，
            有效保障数据一致性与系统性能。
          </li>
          <li>
            负责硬件与IOT平台的对接与开发，构建支持多协议的硬件服务，通过MQTT协议（Mosquitto）和HTTP协议，实现了硬件设备的集中管理和协调调度。
            此服务简化了硬件通信流程，增强了系统的灵活性和可靠性。
          </li>
          <li>
            负责权限模块的架构设计和开发，采用AOP、反射和注解技术，实现高效的权限控制。利用JWT进行安全Token管理，并结合Redis实现了会话存储和快速访问控制。
            此模块包括对按钮权限和角色管理的全面支持，显著提升了系统的安全性和扩展性。
          </li>
          <li>
            设计并实现基于RabbitMQ的消息服务，负责接收和处理来自其他服务的消息，并统一推送到微信服务消息、短信平台、系统内部消息模块。
            显著优化消息的分发流程，确保通知的实时性和准确性。
          </li>
        </ul>
      </div>
    </div>

    <div class="project">
      <div class="project-info">
        <div class="name">CampusMate（校园伙伴）</div>
        <div class="date">2023年6月 至今</div>
      </div>
      <div class="position">Java后端开发 开发组长</div>
      <div class="item"><span>项目架构：</span>SpringBoot + MyBatis + Dynamic-Datasource + WebSocket + Redis +
        Oracle + Elasticsearch + LangChain4j + DeepSeek
      </div>
      <div class="item">
        <span>项目描述：</span>
        一个创新的在线互动招生平台，专为高校设计，帮助学生和教师与潜在的申请者分享他们在校园内的真实生活和经验。游客可以实时在线沟通，参与丰富的互动活动。
        通过增强的互动性和交流机会，提高了学校在优秀学生中的吸引力和申请转化率。平台已升级至 2.0 版本，集成 AI 功能，并成功上架华为云商店。
      </div>
      <div class="item">
        <span>主要职责：</span>
        <ul class="content">
          <li>
            担任开发小组长，主导后端设计与部署，采用Maven多模块架构提升系统复用性与扩展性，并协调前后端协作，指导实习生共同高效完成项目交付。
          </li>
          <li>
            主导后端的设计和开发，负责将系统部署到生产环境并顺利上线。采用Maven多模块架构，使得业务模块得以独立开发和测试，极大地提高了代码
            的复用率和系统的可扩展性。
          </li>
          <li>
            负责 DeepSeekAI 接入，基于 Elasticsearch 实现向量检索和近似 kNN 查询，结合 ONNX 部署模型支持文档驱动的 AI 问答；
            手动实现 AI 聊天池，解决多用户并发访问问题，保障系统稳定性。
          </li>
          <li>
            将业务表与聊天相关的表进行隔离，采用垂直分库、水平分表策略。为不同的学校创建了独立的聊天会话与聊天记录表，
            通过 Dynamic-Datasource 实现多数据源的动态切换和跨数据源事务的管理，有效保障系统的稳定性和扩展性。
          </li>
          <li>
            利用 WebSocket 和 Redis 实现了聊天相关功能，通过缓存聊天会话列表，使用 Redis 的 hash 和 set 数据结构保存会话信息，
            显著提升了消息发送和会话查询的效率。同时，与微信公众号进行对接开发，实现了高校学生和教师在离线状态下通过微信公众号收到消息提醒的功能。
          </li>
        </ul>
      </div>
    </div>

    <div class="project">
      <div class="project-info">
        <div class="name">澳比网络OA系统</div>
        <div class="date">2021年8月 - 2023年5月</div>
      </div>
      <div class="position">Java后端开发</div>
      <div class="item"><span>项目架构：</span>SpringBoot + SpringSecurity + Ebean + Redis + Oracle</div>
      <div class="item">
        <span>项目描述：</span>
        主要用于管理企业内部的各项工作流程和任务，旨在提高团队协作效率。系统涵盖员工管理、任务管理、审批流程等多个模块，并与快手、诺诺等
        第三方合作，实现充值、转账、合同签署等特殊场景功能。
      </div>
      <div class="item">
        <span>主要职责：</span>
        <ul class="content">
          <li>
            主要负责后端代码编写和数据库设计，使用SpringSecurity、Redis、JWT、反射实现组织架构的权限管理，并通过自定义注解实现按钮级的权限控制。
          </li>
          <li>
            从零开始搭建审批流程模块，实现不同业务的流程自定义配置，包括多人审批、审批回退和审批条件等流程细节的定制。为确保流程的灵活性
            和可扩展性，采用模板方法模式和责任链模式，针对不同的业务需求进行定制化处理。
          </li>
          <li>
            与快手平台的对接，通过调用其接口执行用户的交易操作，包括充值、转账和退款等。为了应对并发场景，采用数据库行锁结合超时重试机制，
            确保客户账户、多账户及交易流水的一致性。
          </li>
          <li>
            SQL 查询的优化和系统性能的优化，并参与系统测试和部署工作。使用 JMeter 进行一系列压力测试，根据测试结果采取优化措施，
            确保系统在性能和安全性方面达到最佳状态。
          </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<style scoped>
.container {
  width: 800px;
}

.title {
  font-size: 20px;
  font-weight: bold;
}

hr {
  border: none;
  border-top: 2px solid #333;
  margin-top: 8px;
  margin-bottom: 24px;
}

.project {
  margin-bottom: 20px;
}

.project-info {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-bottom: 8px;
  font-size: 16px;

  .name {
    font-weight: bold;
  }
}

.item {
  margin: 8px 0;
  font-size: 16px;

  span {
    font-weight: bold;
  }
}

.content {
  display: flex;
  flex-direction: column;
  gap: 10px;

  li {
    font-size: 16px;
  }
}
</style>