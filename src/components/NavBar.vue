<script setup lang="ts">
import { RouterLink } from "vue-router";
import IconThor from "@/components/icons/IconThor.vue";
</script>

<template>
  <header class="header">
    <IconThor class="text-blue-500 w-16 h-16" />
    <!-- <div
      class="w-80 bg-blue-500 h-4 flex items-center justify-center text-xs text-white"
    >
      &lt;-- 320px --&gt;
    </div> -->
    <nav class="navbar">
      <RouterLink class="nav-item" to="/">Home</RouterLink>
      <RouterLink class="nav-item" to="/settings">Settings</RouterLink>
      <RouterLink class="nav-item" to="/about">About</RouterLink>
    </nav>
  </header>
</template>
