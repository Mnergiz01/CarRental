<template>
  <div class="min-w-screen flex justify-center relative">
    <!-- Araç Görseli -->
    <img class="object-contain max-w-full h-auto" src="@/assets/Car_1.png" alt="Luxury Car" />

    <!-- Metin ve Buton -->
    <div
      class="absolute top-3/4 right-20 transform -translate-y-1/2 bg-white bg-opacity-75 p-6 rounded-lg w-75 shadow-lg"
      data-aos="fade-left"
      data-aos-duration="1000"
    >
      <h1 class="text-3xl font-bold text-gray-900">Safer, Faster and Comfortable</h1>
      <h3 class="text-lg text-gray-700 mt-2">Get in touch with our luxury cars</h3>
      <button class="mt-4 bg-blue-500 text-white px-6 py-2 hover:bg-blue-600 transition rounded-full">
        Rent Now
      </button>
    </div>
  </div>
</template>