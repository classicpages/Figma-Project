<template>
  <div>
    <nav class="md:flex md:justify-between pt-5">
      <div class="flex text-blue-700 navbar">
        <div class="navbar"><a href="">Home</a></div>
        <div class="navbar"><a href="">About</a></div>
        <div class="navbar"><a href="">Contact</a></div>
      </div>
      <div>
        <a href="/">
          <img src="../assets/Landie.png" alt="Landie Logo" width="75" height="38" />
        </a>
      </div>
      <Button buttonText="Buy Now" color="bg-blue-950" textColor="text-white" />
    </nav>
  </div>
</template>

<script setup>
import Button from '@/components/Button.vue'
</script>

<style scoped>
.navbar {
  width: 200px;
  height: 24px;
  top: 19px;
}
</style>
