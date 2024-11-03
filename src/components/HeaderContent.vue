<script setup lang="ts">

</script>

<template>
  <nav class="px-12 w-full h-[80px] bg-x-black flex items-center justify-between">
    <img src="@/assets/images/logo/logo-join-sistem.png" alt="Join Sistem Logo">
    <ul class="flex gap-4">
      <router-link class="text-white hover:text-x-yellow transition duration-150 ease-in-out" to="/">Home</router-link>
      <router-link class="text-white hover:text-x-yellow transition duration-150 ease-in-out" to="/blogg">Blog</router-link>
      <router-link class="text-white hover:text-x-yellow transition duration-150 ease-in-out" to="/about">AboutUs</router-link>
      <li>
        <router-link class="text-white hover:text-x-yellow transition duration-150 ease-in-out" to="/contact">Contact Us</router-link>
      </li>
    </ul>
    <a href="#" class="bg-x-blue px-4 py-2 rounded-full text-white hover:bg-x-yellow transition duration-150 ease-in-out">Contact Us</a>
  </nav>
</template>
