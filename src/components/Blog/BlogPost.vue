<template>
  <header data-layername="blogHeader" class="flex flex-col">
    <div data-layername="background" class="p-20 w-full bg-gray-100 max-md:px-5 max-md:max-w-full">
      <div class="flex gap-2 max-md:flex-col">
      </div>
    </div>
  </header>

  <section data-layername="allBlogs" class="flex flex-col text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:text-4xl mx-auto max-w-7xl px-8">
    <h2 data-layername="allPosts" class="self-start max-md:text-4xl">
      All posts
    </h2>
    <hr data-layername="allBlogsDivider" class="mt-8 mb-10 w-full border border-zinc-500 opacity-32 max-md:max-w-full" aria-hidden="true">
  </section>

  <section class="blog-cards mx-auto max-w-7xl px-8">
    <div class="flex flex-col gap-10">
      <!-- Artikel 1 -->
      <div class="flex gap-5 items-center max-md:flex-col">
        <img 
          loading="lazy" 
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/dafc832692f064b1e9cede46d64fbd4e375a21b3a6424516083c63b2bfa3e204?placeholderIfAbsent=true&apiKey=d3a84c8091634e1f8eb7b9af0794d8ca" 
          alt="Design tips for designers image" 
          class="object-cover w-[40%] max-md:w-full"
        />
        <div class="w-[60%] max-md:w-full">
          <h2 class="text-pink-600 uppercase tracking-[3px]">STARTUP</h2>
          <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Design tips for designers that cover everything you need</h3>
          <p class="mt-4 leading-7 text-zinc-500">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
      <!-- Artikel 2 -->
      <div class="flex gap-5 items-center max-md:flex-col">
        <img 
          loading="lazy" 
          src="../../assets/images/misc/blog1.png"
          alt="Design tips for designers image" 
          class="object-cover w-[40%] max-md:w-full"
        />
        <div class="w-[60%] max-md:w-full">
          <h2 class="text-pink-600 uppercase tracking-[3px]">BUSINESS</h2>
          <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">How to build rapport with your web design clients</h3>
          <p class="mt-4 leading-7 text-zinc-500">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
      <!-- Artikel 3 -->
      <div class="flex gap-5 items-center max-md:flex-col">
        <img 
          loading="lazy" 
          src="../../assets/images/misc/blog2.png"
          alt="Design tips for designers image" 
          class="object-cover w-[40%] max-md:w-full"
        />
        <div class="w-[60%] max-md:w-full">
          <h2 class="text-pink-600 uppercase tracking-[3px]">STARTUP</h2>
          <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Logo design trends to avoid in 2022</h3>
          <p class="mt-4 leading-7 text-zinc-500">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
      <!-- Artikel 4 -->
      <div class="flex gap-5 items-center max-md:flex-col">
        <img 
          loading="lazy" 
          src="../../assets/images/misc/blog3.png"
          alt="Design tips for designers image" 
          class="object-cover w-[40%] max-md:w-full"
        />
        <div class="w-[60%] max-md:w-full">
          <h2 class="text-pink-600 uppercase tracking-[3px]">TECHNOLOGY</h2>
          <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">8 Figma design systems you can download for free today</h3>
          <p class="mt-4 leading-7 text-zinc-500">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
      <!-- Artikel 5 -->
      <div class="flex gap-5 items-center max-md:flex-col">
        <img 
          loading="lazy" 
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/dafc832692f064b1e9cede46d64fbd4e375a21b3a6424516083c63b2bfa3e204?placeholderIfAbsent=true&apiKey=d3a84c8091634e1f8eb7b9af0794d8ca" 
          alt="Design tips for designers image" 
          class="object-cover w-[40%] max-md:w-full"
        />
        <div class="w-[60%] max-md:w-full">
          <h2 class="text-pink-600 uppercase tracking-[3px]">ECONOMY</h2>
          <h3 class="mt-3 text-4xl font-bold tracking-tighter leading-10 text-gray-800">Font sizes in UI design: The complete guide to follow</h3>
          <p class="mt-4 leading-7 text-zinc-500">Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Pagination -->
  <nav aria-label="Pagination" data-layername="pagination" class="flex justify-center items-center gap-4 font-bold text-center p-2 mx-auto">
    <button 
      data-layername="prev" 
      class="flex items-center text-lg text-gray-500 hover:text-blue-600 transition-colors duration-200 focus:outline-none focus:ring-0"
      @click="goToPrevious"
    >
      &lt; <span class="ml-1">Prev</span>
    </button>
    <router-link
      to="/blogpost"
      class="flex items-center text-lg text-gray-500 hover:text-blue-600 transition-colors duration-200 focus:outline-none focus:ring-0"
    >
      <span class="mr-1">Next</span> &gt;
    </router-link>
  </nav>
</template>

<script>
export default {
  name: 'BlogCards',
  methods: {
    goToPrevious() {
      // Implement previous page logic
    },
    goToNext() {
      // Implement next page logic
    }
  }
}
</script>