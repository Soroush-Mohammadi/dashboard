<template>

  <transition name="menu">
    <div>
      <div
        class="bg-black text-white flex flex-col items-center py-4 rounded-sm"
        :class="{ 'w-44': props.menu, 'w-16': !props.menu }"
      >
        <!-- User Badge -->
        <div class="mb-8 flex justify-center">
          <div class="flex items-center justify-center rounded-full text-black text-sm">
           <img src="/profile.png"  class="w-16" alt="" :class="{ 'w-10' : !props.menu}">
          </div>
        </div>

        <!-- Menu Items -->
        <div class="flex flex-col space-y-4 w-full">
          <div
            class="flex items-center px-2"
            v-for="item in menus"
            :key="item.name"
          >
            <NuxtLink
              :to="item.src"
              class="flex items-center justify-center space-x-4 hover:text-yellow-500 py-2 my-4"
        
            >
              <span class="material-icons mx-3"
              
              >{{ item.name }}</span>
              <!-- Show title only when menu is expanded -->
              <p
                v-if="props.menu"
                class="text-sm  font-medium transition-opacity duration-300"
              >
                {{ item.name }}
              </p>
            </NuxtLink>
          </div>
        </div>

        <!-- Logout Button -->
        <div class="mt-10 flex justify-center">
          <span class="material-icons cursor-pointer hover:text-red-500">
            power_settings_new
          </span>
        </div>
      </div>
    </div>
  </transition>
</template>


<script setup>
import { watch } from 'vue'
const props = defineProps(['menu'])

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
    name: "chat",
    src: '/community'
  },
  {
    name: "settings",
    src : '/settings'
  },

];
</script>


<style>
/* Base Menu Style */
.menu {
  background-color: #f4f4f4;
  padding: 16px;
  overflow: hidden;
  border: 1px solid #ddd;
}

/* Transition Styles */
.menu-enter-active,
.menu-leave-active {
  transition: max-height 0.5s ease, opacity 0.5s ease;
}

.menu-enter-from,
.menu-leave-to {
  max-height: 0;
  opacity: 0;
}

.menu-enter-to,
.menu-leave-from {
  max-height: 300px; /* Adjust based on your menu height */
  opacity: 1;
}
</style>
