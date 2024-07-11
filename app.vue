<template>
  <NuxtLayout>
    <NuxtPage/>
  </NuxtLayout>
</template>
<style>
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
body {
  background-color: white;
  color: #0D0D0D;
  transition: background-color 0.5s ease, color 0.5s ease;
}
.dark body {
  background-color: #0D0D0D;
  color: white;
}
</style>

<script setup lang="ts">

</script>
