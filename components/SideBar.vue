<template>
  <div class="bg-black text-white w-20 flex flex-col items-center py-4">
    <div class="mb-8">
      <div class="w-6 rounded-full bg-yellow-600">12</div>
    </div>
    <div class="flex flex-col space-y-8">
      <div class="flex flex-col items-center" v-for="item in menus" :key="item">
        <NuxtLink :to="item.src">
            <span class="material-icons">{{item.name }}</span>
        </NuxtLink>
      </div>

    </div>
    <div class="mt-auto flex flex-col items-center">
      <span class="material-icons">  power_settings_new </span>
    </div>
  </div>
</template>

<script setup>
const menus = [
  {
    name: "home",
    src: '/',
  },
  {
    name: "folder",
    src : '/lessons'
  },
  {
    name: "school",
    src : '/acheivments'
  },
  {
    name: "quiz",
    src : '/quiz'
  },
  {
    name: "leaderboard",
    src : '/leaderboard'
  },
  {
    name: "chat_bubble",
    src: '/community'
  },
  {
    name: "settings",
    src : '/settings'
  },

];
</script>
