<template>
  <h1>me view page</h1>
  <div>这里展示用户信息</div>
</template>

<script setup>
import MathUtil from '@/utils/MathUtil.js'
name = 'ZhangSan'
console.log(MathUtil(1, 2))
for (let i = 0; i < 10; i++) {
  console.log(i)
  console.log(MathUtil(i, i + 1))
}

console.log(name)

不小心打错了
</script>

<style scoped></style>
