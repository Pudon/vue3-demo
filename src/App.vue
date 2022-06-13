<script setup lang="ts">
const dealClick = () => {
  ElMessage.error('消息')
}
</script>

<template>
  <el-button @click="dealClick">点击展示消息</el-button>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
