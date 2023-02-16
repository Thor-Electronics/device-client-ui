<script setup lang="ts"></script>

<template>
  <form
    action="/account-settings"
    class="flex flex-col gap-4 bg-white w-full rounded-xl p-3"
  >
    <h1 class="text-center text-lg font-bold">Account Settings</h1>

    <label class="row">
      Building Token:
      <input
        class="font-mono"
        type="text"
        name="buildingToken"
        placeholder="7f8da9f789da07f890ad"
        required
      />
    </label>

    <label class="row">
      Email:
      <input
        type="email"
        name="ownerEmail"
        placeholder="user@gmail.com"
        required
      />
    </label>

    <label class="row">
      Device Name:
      <input
        type="text"
        name="deviceName"
        placeholder="Bedroom Lights"
        required
      />
    </label>

    <label class="row">
      Device Type:
      <select
        type="text"
        name="deviceName"
        placeholder="Bedroom Lights"
        required
      >
        <!-- OPTIONS -->
      </select>
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
