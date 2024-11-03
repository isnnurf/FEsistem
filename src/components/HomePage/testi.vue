<template>
    <section class="flex flex-col items-center py-10 bg-orange-50">
      <div class="flex w-full max-w-6xl justify-between items-center">
        <!-- Left Section: Testimonials Header -->
        <div class="flex flex-col">
          <h2 class="uppercase text-sm tracking-widest text-gray-500">
            TESTIMONIALS
          </h2>
          <h3 class="mt-2 text-4xl font-bold text-gray-800">
            What people say about our blog
          </h3>
          <p class="mt-4 text-zinc-500 text-lg">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.
          </p>
        </div>
  
        <!-- Divider Line -->
        <div class="border-l border-gray-300 h-48 mx-8"></div>
  
        <!-- Right Section: Testimonial Content -->
        <div class="flex flex-col w-1/2">
          <blockquote class="text-2xl font-bold text-gray-800">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </blockquote>
          <div class="flex items-center justify-between mt-10">
            <!-- Testimonial Author Info -->
            <div class="flex items-center">
              <img
                src="https://cdn.builder.io/api/v1/image/assets/TEMP/02d592130db1c41c9a9757680afcdcdffaa6660ac2194ecb46c25b2f9bc54b98?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2"
                alt="Profile picture of Jonathan Vallem"
                class="w-12 h-12 rounded-full"
              />
              <div class="ml-4">
                <h4 class="text-lg font-bold text-gray-800">
                  Jonathan Vallem
                </h4>
                <p class="text-zinc-500 text-sm">
                  New York, USA
                </p>
              </div>
            </div>
  
            <!-- Navigation Arrows -->
            <div class="flex gap-4">
              <button class="p-2 rounded-full bg-gray-200">
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/TEMP/d3f5ae0b05f88175949425804e6e1196fc776b109748d2aa18fea9d1861879d4?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2"
                  alt="Previous"
                  class="w-6 h-6"
                />
              </button>
              <button class="p-2 rounded-full bg-gray-800">
                <img
                  src="https://cdn.builder.io/api/v1/image/assets/TEMP/07b676eb085c0c013528d5ff088726665c65f255584b47cb51e5c4e4b02268d0?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2"
                  alt="Next"
                  class="w-6 h-6 text-white"
                />
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>
  </template>
  
  <style scoped>
  .border-l {
    width: 1px;
    height: auto;
  }
  </style>
  