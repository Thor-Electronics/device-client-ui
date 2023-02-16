<template>
  <div class="about p-2">
    <h1 class="text-xl font-bold text-center mb-4">ABOUT</h1>
    <div
      class="about-card bg-white flex flex-col items-stretch p-3 rounded-xl shadow-md gap-4"
    >
      <div>APP VERSION</div>
      <div>DEVICE INFO AND OTHER INFO</div>
      <div>CONTACT INFO</div>
      <div>SERVER STATUS</div>
      <div>DEBUG INFO</div>
      <div>LINK TO DEBUG PAGE</div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
