<script setup>

</script>

<template>
  <div class="container">
    <div class="title">
      教育经历
    </div>
    <hr/>
    <div class="school-info">
      <div class="name">西北工业大学</div>
      <div class="date">2022年3月 - 2024年6月</div>
    </div>
    <div class="position">计算机科学与技术 本科</div>

<!--    <div class="school-info">-->
<!--      <div class="name">陕西师范大学</div>-->
<!--      <div class="date">2022年3月 - 2024年6月</div>-->
<!--    </div>-->
<!--    <div class="position">计算机科学与技术 本科</div>-->
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

.school-info {
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