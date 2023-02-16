<script setup lang="ts">
import { RouterView } from "vue-router";
import NavBar from "@/components/NavBar.vue";
import Footer from "./components/FooterComponent.vue";
</script>

<template>
  <NavBar />
  <!-- <main class="main"> -->
  <RouterView />
  <!-- </main> -->
  <Footer />
</template>

<style scoped></style>
