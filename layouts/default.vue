<script setup lang="ts">
import AppHeader from "~/components/bars/Header/AppHeader.vue";


</script>

<template>
  <div class="flex flex-col h-screen">
    <AppHeader />
    <div class="flex-1 overflow-y-auto">
      <slot />
    </div>
  </div>
</template>

<style scoped>

</style>
