<template>
  <q-page class="q-pa-md flex flex-center">
    <div class="row justify-center">
      <div class="col-6 col-md-3">
        <a class="flex justify-center" href="https://vitejs.dev" target="_blank">
          <img src="~assets/quasar.svg" class="logo quasar" alt="Quasar logo" />
        </a>
      </div>
      <div class="col-6 col-md-3">
        <a class="flex justify-center" href="https://vitejs.dev" target="_blank">
          <img src="~assets/vite.svg" class="logo vite" alt="Vite logo" />
        </a>
      </div>
      <div class="col-6 col-md-3">
        <a class="flex justify-center" href="https://tauri.app" target="_blank">
          <img src="~assets/tauri.svg" class="logo tauri" alt="Tauri logo" />
        </a>
      </div>
      <div class="col-6 col-md-3">
        <a class="flex justify-center" href="https://vuejs.org/" target="_blank">
          <img src="~assets/vue.svg" class="logo vue" alt="Vue logo" />
        </a>
      </div>
    </div>
  </q-page>
</template>

<script setup>
defineOptions({
  name: 'IndexPage'
});
</script>
