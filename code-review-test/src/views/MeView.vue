<template>
  <h1>me view page</h1>
  <div>这里展示用户信息</div>
</template>

<script setup>
import { HomeView } from './HomeView.vue'
name = 'ZhangSan'
age = 23

console.log(`my name is ${name}, age is ${age}`)
</script>

<style scoped></style>
