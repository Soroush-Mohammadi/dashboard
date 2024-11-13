<template>
  <div class="h-14 flex items- shadow-md">
   <button @click="handleMenu">
    <span class="material-icons"> arrow_right_alt </span>
   </button>
    <input type="text" placeholder="Search" class="m-3 p-2 border rounded" />
  </div>
</template>

<script setup>
import {ref, watch} from 'vue'
const toggle = ref(false);

const emit = defineEmits(['toggle-menu'])
const handleMenu = () => toggle.value = !toggle.value

watch(toggle, () => emit('toggle-menu', toggle.value))

</script>
