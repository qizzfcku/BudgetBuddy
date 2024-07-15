<script setup lang="ts">

import SideBar from "~/components/bars/SideBar/SideBar.vue";
</script>

<template>
  <div class="flex h-full">
    <SideBar/>
    <div class="flex flex-col flex-1 ml-[16.66667%] overflow-y-auto">
      <div class="h-16 w-full flex justify-end items-center border">
        <span class="text-2xl font-bold" >Баланс</span>
        <span class="">+</span>
      </div>
      <div class="flex-1">

      </div>
    </div>
  </div>
</template>


<style scoped>

</style>
