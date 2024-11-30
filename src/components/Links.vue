<script setup>
defineProps({
  msg: String,
})
</script>

<template>
  <h1>{{ msg }}</h1>
  <p>
    查看
    <a href="https://vuejs.org/guide/quick-start.html#local" target="_blank">create-vue</a>，
    官方的 Vue + Vite 启动模板
  </p>
  <p>
    了解更多关于 Vue 的 IDE 支持，请访问
    <a href="https://vuejs.org/guide/scaling-up/tooling.html#ide-support" target="_blank">Vue 文档扩展指南</a>
  </p>
  <p class="read-the-docs">点击 Vite 和 Vue 的图标了解更多</p>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>