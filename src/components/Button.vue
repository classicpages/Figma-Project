<template>
  <div class="mt-8 md:mt-0">
    <a
      href="#"
      :class="color + ' ' + textColor"
      class="mr-5 my-5 text-xs font-semibold uppercase py-3 px-10"
    >
      {{ buttonText }}
    </a>
  </div>
</template>

<script setup>
import { defineProps } from 'vue'
defineProps({
  buttonText: {
    type: String,
    required: true
  },
  color: {
    type: String,
    required: true
  },
  textColor: {
    type: String,
    required: true
  }
})
</script>
