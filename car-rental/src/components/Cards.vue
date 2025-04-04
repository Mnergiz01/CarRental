<template>
    <div class="mx-20">
      <h1 class="text-center mb-20 text-3xl font-semibold">We have everything you need</h1>
  
      <div class="flex flex-wrap gap-6 justify-center">
        <card v-for="i in 4" :key="i" />
      </div>
    </div>
  </template>
  
  <script setup>
  import card from '@/components/minor/Card.vue'
  </script>
  