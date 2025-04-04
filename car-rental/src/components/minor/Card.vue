<template>
  <div class="flex flex-col gap-4 w-80 h-auto bg-gray-900 rounded-2xl shadow-xl p-5" data-aos="fade-up">
    <!-- Başlık -->
    <div class="text-center" data-aos="fade-down">
      <h1 class="text-2xl font-bold text-white">Dodge Charger</h1>
    </div>

    <!-- Araç Görseli -->
    <div class="w-full flex justify-center" data-aos="zoom-in">
      <img class="object-contain max-h-40" src="@/assets/car_2.png" alt="Dodge Charger">
    </div>

    <!-- Araç Bilgileri -->
    <div class="px-4" data-aos="fade-up" data-aos-delay="100">
      <h3 class="text-lg font-semibold text-gray-300">2016</h3>
      <div class="flex flex-row justify-between text-sm text-gray-400 mt-1">
        <span>15K Miles</span>
        <span>Auto</span>
        <span>Gas</span>
      </div>
    </div>

    <!-- Fiyat -->
    <div class="text-center text-xl font-bold text-green-400" data-aos="fade-up" data-aos-delay="200">
      $10,000
    </div>

    <!-- Buton -->
    <div class="flex justify-center mt-2" data-aos="fade-up" data-aos-delay="300">
      <button class="bg-blue-600 hover:bg-blue-700 text-white font-semibold rounded-full px-10 py-2 transition duration-200">
        Rent
      </button>
    </div>
  </div>
</template>

<script setup>
import AOS from 'aos';
import 'aos/dist/aos.css';

AOS.init(); // AOS'u başlatıyoruz
</script>
