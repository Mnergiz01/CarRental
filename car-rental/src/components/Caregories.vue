<template>
    <div class="mt-35">
        <h1 class="text-center font-bold text-2xl">OUR LUXURY BRAND</h1>
        <div class="mx-50 mt-15 flex flex-row gap-25 ">
            <categories v-for="i in 5" :key="i"></categories>
        </div>
    </div>
</template>
<script setup>
import categories from '@/components/minor/categories.vue'
</script>