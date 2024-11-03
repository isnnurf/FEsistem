<template>
  <main data-layername="myBlog" class="blog-container mx-auto max-w-5xl px-10 py-10 border border-blue-500">
    <div class="flex flex-col">
      <!-- Header -->
      <h1 class="text-5xl font-bold tracking-tighter text-gray-800 mb-10">My Posts</h1>
      
      <!-- Section 1 -->
      <div class="flex gap-8 mb-10">
        <!-- Image Section -->
        <div class="w-[40%]">
          <img 
            loading="lazy" 
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/7a0cfd0b5f4bac1070110b31f5611e8edaf3d046aecde01dc829c8565e0f4e88?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" 
            alt="Blog post featured image" 
          />
        </div>
        
        <!-- Content Section -->
        <div class="w-[60%]">
          <span class="text-sm uppercase text-amber-500 font-bold tracking-widest">Business</span>
          <h2 class="text-3xl font-bold mt-2 mb-3 text-gray-800">Font sizes in UI design: The complete guide to follow</h2>
          <p class="text-gray-500 leading-relaxed">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>

      <!-- Section 2 -->
      <div class="flex gap-8">
        <!-- Image Section -->
        <div class="w-[40%]">
          <img 
            loading="lazy" 
            src="https://cdn.builder.io/api/v1/image/assets/TEMP/ca902affa6ca9d3191f1c419b95251b420de6faa3e6ebeeb56b702de796f1699?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" 
            alt="Blog post featured image" 
          />
        </div>
        
        <!-- Content Section -->
        <div class="w-[60%]">
          <span class="text-sm uppercase text-amber-500 font-bold tracking-widest">Economy</span>
          <h2 class="text-3xl font-bold mt-2 mb-3 text-gray-800">How to build rapport with your web design clients</h2>
          <p class="text-gray-500 leading-relaxed">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
.blog-container {
  border-width: 0px;
}
</style>
