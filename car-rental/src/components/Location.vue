<template>
    <div class="p-5" data-aos="fade-up" data-aos-duration="1000">
      <div class="flex flex-col items-center text-center" data-aos="zoom-in" data-aos-delay="200">
        <h1 class="text-2xl font-bold">Book Your Dream Car Now!</h1>
        <p class="w-full md:w-2/3 mt-2">
          Rent a car online now from one of our worldwide locations. With over 20 years’ experience in luxury car and customer services, all we need is your ID and you can book any car.
        </p>
      </div>
  
      <div
        class="flex flex-col md:flex-row gap-5 mt-6 items-center justify-center"
        data-aos="fade-up"
        data-aos-delay="400"
      >
        <select class="border p-2 rounded w-full md:w-48">
          <option value="">Select Car Type</option>
          <option value="sedan">Sedan</option>
          <option value="suv">SUV</option>
          <option value="convertible">Convertible</option>
          <option value="luxury">Luxury</option>
        </select>
  
        <input type="search" placeholder="Pick-up Location" class="border p-2 rounded w-full md:w-48" />
        <input type="search" placeholder="Drop-off Location" class="border p-2 rounded w-full md:w-48" />
  
        <input type="date" class="border p-2 rounded w-full md:w-40" />
        <input type="date" class="border p-2 rounded w-full md:w-40" />
  
        <button class="bg-blue-500 text-white px-6 py-2 rounded hover:bg-blue-700">Book</button>
      </div>
    </div>
  </template>
  