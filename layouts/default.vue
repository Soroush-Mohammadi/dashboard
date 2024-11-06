<template>
  <div class="flex h-screen">
    <!-- Sidebar -->
    <SideBar />
    <!-- Main Content -->
    <div class="flex-1 rounded-lg m-4">
      <!-- Content goes here -->
      <slot />
    </div>
  </div>
</template>
