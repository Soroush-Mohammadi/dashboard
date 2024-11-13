<template>
  <div class="flex">
    <SideBar :menu="menu"/>
    <div class="flex-1 rounded-lg m-4">
      <TopBar @toggle-menu="handleToggleMenu"/>
    </div>
  </div>
</template>


<script setup>
import { ref } from 'vue'
const menu = ref(false)
const handleToggleMenu = (val) => {
  menu.value = val
  console.log('menu state changed to ' + val)
}


</script>