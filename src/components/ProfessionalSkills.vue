<script setup>

</script>

<template>
  <div class="container">
    <div class="title">
      专业技能
    </div>
    <hr/>
    <ul class="content">
      <li>熟练掌握 Java 编程语言，熟悉集合、JVM及垃圾回收机制、并发编程，具有良好的编程习惯</li>
      <li>熟悉 MySql 数据库，熟悉索引、锁机制、事务机制、MVCC、SQL优化等，熟悉 Oracle 数据库</li>
      <li>熟练使用 SpringBoot、Spring、Mybatis 等常用框架，能够高效开发复杂业务逻辑的需求</li>
      <li>熟练使用 Redis，深入理解核心数据结构以及使用场景，了解缓存穿透、击穿、雪崩、双写一致等</li>
      <li>熟悉 RabbitMQ、Elasticsearch 中间件</li>
      <li>熟悉常用设计模式，了解 JavaScript、Vue、Flutter 等前端技术</li>
      <li>熟练使用 Linux、Docker 等开发工具</li>
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

.content {
  display: flex;
  flex-direction: column;
  gap: 10px;
}
</style>