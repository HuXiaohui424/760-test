<template>
  <div class="about">
    <h1>Hi View page<h1>
    <div>这是一个打招呼页面，你看到它就证明我在向你打招呼</div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>

<script>
name = 'xiaoming'
age = 18
console.log(`hello, i'm ${name}, i'm ${age} years old.`)
</script>
