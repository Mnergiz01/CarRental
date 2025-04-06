<template>
    <div class="flex flex-col gap-20">
        <Navbar></Navbar>
        <Upperarea></Upperarea>
        <Location></Location>
        <Ourservices></Ourservices>
        <Cards></Cards>
        <Categories></Categories>
        <submit></submit>
        <Footer></Footer>
    </div>
</template>

<script setup>

import Navbar from '@/components/Navbar.vue'
import Upperarea from '@/components/Upperarea.vue'
import Location from '@/components/Location.vue'
import Ourservices from '@/components/Ourservices.vue'
import Cards from '@/components/Cards.vue'
import Categories from '@/components/Caregories.vue'
import submit from '@/components/submit.vue'
import Footer from '@/components/Footer.vue'
</script>
