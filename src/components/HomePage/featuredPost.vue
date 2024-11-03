<template>
  <section class="p-8 grid grid-cols-1 md:grid-cols-2 gap-8">
    <!-- Featured Post Section -->
    <div>
      <h2 class="text-3xl font-bold mb-4">Featured Post</h2>
      <div class="bg-white shadow-lg p-4">
        <img src="/assets/pexels-photo-1838640.jpg" alt="Featured" class="w-full h-64 object-cover">
        <h3 class="text-xl font-bold mt-4 text-blue-900">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</h3>
        <p class="text-sm text-gray-600 mt-2">By <span class="text-orange-500">John Doe</span> | May 23, 2022</p>
        <p class="mt-4 text-gray-700">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
        <button class="bg-blue-600 hover:bg-blue-500 px-6 py-3 mt-4 text-white">Read More ></button>
      </div>
    </div>

    <!-- All Posts Section -->
    <div>
      <h2 class="text-3xl font-bold mb-4">All Posts</h2>
      <div class="flex flex-col space-y-4">
        <div class="bg-white shadow-lg p-4 hover:bg-yellow-50">
          <p class="text-sm text-gray-600">By <span class="text-orange-500">John Doe</span> | Aug 23, 2021</p>
          <h4 class="font-bold mt-2 text-blue-900">8 Figma design systems that you can download for free today.</h4>
        </div>
        <div class="bg-white shadow-lg p-4 hover:bg-yellow-50">
          <p class="text-sm text-gray-600">By <span class="text-orange-500">John Doe</span> | Aug 23, 2021</p>
          <h4 class="font-bold mt-2 text-blue-900">8 Figma design systems that you can download for free today.</h4>
        </div>
        <div class="bg-white shadow-lg p-4 hover:bg-yellow-50">
          <p class="text-sm text-gray-600">By <span class="text-orange-500">John Doe</span> | Aug 23, 2021</p>
          <h4 class="font-bold mt-2 text-blue-900">8 Figma design systems that you can download for free today.</h4>
        </div>
      </div>
      <a href="#" class="text-blue-600 font-semibold text-right block mt-4 hover:underline">View All</a>
    </div>
  </section>
</template>

<style scoped>
/* Jika kamu ingin menambahkan styling kustom, bisa dilakukan di sini */
</style>
