<template>
    <section class="flex justify-center mt-10">
      <div class="flex flex-col items-center max-w-[407px]">
        <h2 class="z-10 self-stretch mt-0 w-full text-4xl font-bold tracking-tighter leading-10 text-center text-gray-800">
          Join our team to be a part of our story
        </h2>
        <p class="mt-1 text-base leading-7 text-center text-zinc-500"> <!-- Rata tengah dan tidak bold -->
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
        </p>
        <button 
          class="gap-3 px-12 py-4 mt-8 text-lg leading-none text-white bg-blue-600 hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500 focus:ring-offset-2"
          @click="handleJoinClick"
          aria-label="Join our team"
        >
          Join Now
        </button>
      </div>
    </section>
  </template>
  
  <script>
  export default {
    name: 'JoinTeam',
    methods: {
      handleJoinClick() {
        // Handle join button click
        console.log('Join button clicked!'); // Tambahkan log untuk pengujian
      }
    }
  }
  </script>
  
  <style scoped>
  .builder-component {
    max-width: none !important;
  }
  </style>
  