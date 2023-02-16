<script setup lang="ts">
import { RouterLink } from "vue-router";
</script>

<template>
  <form
    action="/wifi-settings"
    class="flex flex-col gap-4 bg-white w-full rounded-xl shadow p-3"
  >
    <h1 class="text-center text-lg font-bold">WiFi Settings</h1>

    <label class="row">
      WiFi SSID:
      <input type="text" name="ssid" placeholder="My House Modem" />
    </label>

    <label class="row">
      WiFi Password:
      <input
        type="password"
        name="password"
        placeholder="Password to connect to WiFi ..."
      />
    </label>

    <div class="buttons">
      <button class="btn bg-blue-500" type="submit">Save</button>
      <RouterLink class="btn bg-slate-400" to="/">Cancel</RouterLink>
    </div>
  </form>
</template>

<style scoped>
.buttons {
  display: flex;
  justify-content: flex-end;
  gap: 0.5rem;
}
</style>
