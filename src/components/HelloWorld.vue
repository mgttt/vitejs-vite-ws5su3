<script setup>
import Counter from './Counter.vue'
import Links from './Links.vue'
import Logo from './Logo.vue'

defineProps({
  msg: String,
})
</script>

<template>
  <Logo />
  <Links :msg="msg" />
  <Counter />
</template>