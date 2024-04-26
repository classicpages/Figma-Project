<script setup>
import Header from './components/Header.vue'
import HeroSection from '@/components/HeroSection.vue'
</script>

<template>
  <div class="img bg-no-repeat bg-right bg-contain container ml-32 h-screen">
    <Header />
    <HeroSection />
  </div>
</template>

<style scoped>
.img {
  background-image: url(/src/assets/designer_1.png);
}
</style>
