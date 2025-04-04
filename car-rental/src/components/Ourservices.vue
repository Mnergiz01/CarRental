<template>
  <div class="flex flex-col lg:flex-row justify-between items-center px-6 lg:px-60 py-30">
    <!-- Image Section -->
    <div
      class="w-full lg:w-1/2 flex justify-center"
      data-aos="fade-right"
      data-aos-duration="1000"
    >
      <img class="object-contain max-w-full h-auto" src="@/assets/car_2.png" alt="Car Image" />
    </div>

    <!-- Services Section -->
    <div
      class="w-full lg:w-1/2 mt-10 lg:mt-0"
      data-aos="fade-left"
      data-aos-duration="1000"
    >
      <h1 class="text-3xl font-bold ms-35 mb-10">Our Services</h1>
      <ul class="space-y-8">
        <li data-aos="fade-up" data-aos-delay="100">
          <div>
            <h2 class="text-xl font-semibold">Car Here</h2>
            <p class="text-gray-600">We pride ourselves in always going the extra mile for our customers.</p>
          </div>
        </li>
        <li data-aos="fade-up" data-aos-delay="200">
          <div>
            <h2 class="text-xl font-semibold">Car Sales</h2>
            <p class="text-gray-600">We pride ourselves in always going the extra mile for our customers.</p>
          </div>
        </li>
        <li data-aos="fade-up" data-aos-delay="300">
          <div>
            <h2 class="text-xl font-semibold">Hire a Driver</h2>
            <p class="text-gray-600">We pride ourselves in always going the extra mile for our customers.</p>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>
