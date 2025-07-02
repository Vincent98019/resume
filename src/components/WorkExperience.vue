<script setup>

</script>

<template>
  <div class="container">
    <div class="title">
      工作经历
    </div>
    <hr/>
    <div class="company-info">
      <div class="name">杭州青蓝红科技有限公司</div>
      <div class="date">2021年5月 至今</div>
    </div>
    <div class="position">Java后端开发工程师 研发部门</div>
    <ul class="content">
      <li>根据项目进行技术选型，搭建技术框架；</li>
      <li>根据产品功能进行服务拆分、数据表设计，对业务模块的编码和测试，编写相关接口文档；</li>
      <li>负责公司核心系统的核心模块代码实现，以及底层架构的代码实现；</li>
      <li>负责业务场景可能用的技术前瞻性调研；</li>
      <li>担任开发小组长，采用敏捷开发模式，带领团队高效完成开发任务，并负责实习生的业务与技术指导。</li>
    </ul>
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

.company-info {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  margin-bottom: 8px;

  .name {
    font-weight: bold;
  }
}

.content {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
</style>