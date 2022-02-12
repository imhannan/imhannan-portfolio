<script setup>
import TheHeader from "./components/TheHeader.vue";
import TheFooter from "./components/TheFooter.vue";
import TheMain from "./components/TheMain.vue";
</script>

<template>
  <header
    class="container-helper container text-base sm:text-lg md:text-xl lg:text-2xl"
  >
    <the-header />
  </header>

  <main class="col-spacing mb-4 flex flex-col sm:mb-8 md:mb-12 lg:mb-16">
    <the-main />
  </main>
  <footer class="container-helper container">
    <the-footer />
  </footer>
</template>

<style></style>
