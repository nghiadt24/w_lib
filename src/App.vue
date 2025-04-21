<script setup>
import mainNav from './components/mainNav.vue';
import heroSection from './components/heroSection.vue';
import CategorySection from './components/CategorySection.vue';
</script>

<template>
  <header>
    <mainNav />
  </header>
  <main>
    <heroSection />
    <CategorySection />
  </main>
</template>

<style scoped>
  header {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: transparent;
  }
</style>
