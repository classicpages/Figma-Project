<template>
  <div>
    <nav class="md:flex md:justify-between pt-5">
      <div class="flex text-blue-700">
        <div class="mx-10"><a href="">Home</a></div>
        <div class="mx-10"><a href="">About</a></div>
        <div class="mx-10"><a href="">Contact</a></div>
      </div>
      <div>
        <a href="/">
          <img src="../assets/Landie.png" alt="Landie Logo" width="75" height="38" />
        </a>
      </div>
      <Button buttonText="Buy Now" />
    </nav>
  </div>
</template>

<script setup>
import Button from '@/components/Button.vue'
</script>
