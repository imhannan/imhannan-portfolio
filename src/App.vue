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

  <main
    class="mb-4 flex flex-col space-y-4 sm:mb-8 sm:space-y-8 md:mb-12 md:space-y-12 lg:mb-16 lg:space-y-16"
  >
    <the-main />
  </main>
  <footer class="container-helper container">
    <the-footer />
  </footer>
</template>

<style></style>
