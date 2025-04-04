<template>
    <div class="relative mx-20 my-20">
      <!-- Görsel -->
      <img src="@/assets/search.png" class="object-cover w-full h-100 rounded-lg shadow-lg" alt="Search" />
  
      <!-- Orta Yazı -->
      <div class="absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-white space-y-2">
        <p class="text-3xl font-bold">Become a Driver</p>
        <span class="block text-lg">Your time. Your goals. You're the boss.</span>
        <span class="block text-sm text-gray-200">Subscribe and join us</span>
      </div>
  
      <!-- Arama Inputu -->
      <div class="absolute top-5 left-1/2 transform -translate-x-1/2 w-1/2 bg-white rounded-full shadow-lg">
        <input
          type="text"
          placeholder="Email..."
          class="w-full px-5 py-3 rounded-full shadow-md border border-gray-300 focus:outline-none focus:ring-2 focus:ring-blue-400"
        />
      </div>
    </div>
  </template>
  