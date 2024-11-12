<script setup>
  import { RouterView } from 'vue-router';
</script>

<template>
  <div>
    <RouterLink to="/">首页</RouterLink>
    <RouterLink to="/about">关于</RouterLink>
  </div>
  <RouterView />
</template>

<style scoped></style>
