<script setup>
import { ref } from 'vue'

const count = ref(0)

const increment = () => {
  count.value++
}
</script>

<template>
  <div class="card">
    <button type="button" @click="increment">count is {{ count }}</button>
    <p>
      编辑 <code>components/Counter.vue</code> 来测试热更新
    </p>
  </div>
</template>

<style scoped>
.card {
  padding: 2em;
}
</style>