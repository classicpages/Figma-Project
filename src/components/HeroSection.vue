<template>
  <section>
    <div class="lorem mt-36">
      <div class="text-left font-medium text-6xl leading-7">
        <p class="text-4xl h-10">Introduce Your Product</p>
        <p class="pt-3 text-4xl leading-7">Quickly & Effectively</p>
      </div>
      <div class="mt-7 text-blue-700 leading-7">
        <p>
          Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aenean commodo ligula eget
          dolor. Aenean massa. Cum sociis natoque penatibus et magnis dis parturient montes,
          nascetur ridiculus mus. Donec quam felis, ultricies nec, pellentesque eu, pretium quis,
          sem. Nulla consequat massa quis enim.
        </p>
      </div>
      <div class="flex mt-20">
        <Button buttonText="Purchase UI Kit" />
        <Button buttonText="Learn More" />
      </div>
    </div>
  </section>
</template>

<script setup>
import Button from '@/components/Button.vue'
</script>

<style scoped>
.lorem {
  width: 540px;
  height: 421px;
}
</style>
