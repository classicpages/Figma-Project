<script setup>
import Header from './components/Header.vue'
import HeroSection from '@/components/HeroSection.vue'
import Sectiontwo from '@/components/Sectiontwo.vue'
import Sectionthree from '@/components/Sectionthree.vue'
import Sectionfour from '@/components/Sectionfour.vue'
import Sectionfive from '@/components/Sectionfive.vue'
import Footer from '@/components/Footer.vue'
</script>

<template>
  <div class="img bg-no-repeat bg-right bg-contain container ml-16 h-screen">
    <Header />
    <HeroSection />
    <Sectiontwo />
    <Sectionthree />
    <Sectionfour />
    <Sectionfive />
    <Footer />
  </div>
</template>

<style scoped>
.img {
  background-image: url(/src/assets/designer_1.png);
}
</style>
