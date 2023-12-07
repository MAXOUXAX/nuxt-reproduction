<template>
  <div>
    <NuxtLink to="/">Root route</NuxtLink>
    <NuxtLink to="/b">Route B</NuxtLink>
    <NuxtLink to="/c">Route C</NuxtLink>
  </div>
</template>
<style scoped>
div{
  display: flex;
  flex-direction: row;
  gap: 1rem;
}
</style>