<template>
  <MainLayout>
<!-- Hero Section -->
<article 
      data-layername="homeHero" 
      class="relative flex items-center justify-between w-full min-h-[720px] bg-black text-white"
      aria-labelledby="heroTitle" aria-describedby="heroDescription"
    >
      <!-- Text content on the left -->
      <div class="relative z-10 flex flex-col items-start justify-center px-20 py-40 max-md:px-5 max-md:py-24">
        <header class="font-semibold leading-none uppercase tracking-[3px]">
          <span class="font-medium">Posted on</span>
          <strong class="font-black">startup</strong>
        </header>
        
        <h1 
          id="heroTitle" 
          data-layername="stepByStepGuideToChoosingGreatFontPairs" 
          class="mt-6 text-6xl tracking-tighter leading-[64px] w-[803px] max-md:max-w-full max-md:text-4xl max-md:leading-[51px]"
        >
          Step-by-step guide to choosing great font pairs
        </h1>
        
        <p id="heroDescription" class="mt-6 leading-7">
          By <span class="text-blue-600">James West</span> | 
          <time datetime="2022-05-23" class="text-white">May 23, 2022</time>
        </p>
        
        <p 
          data-layername="description" 
          class="mt-4 leading-7 w-[599px] max-md:max-w-full"
        >
          Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
        </p>
        
        <button 
          data-layername="button"
          class="gap-3 px-12 py-4 mt-12 text-lg font-semibold text-white bg-blue-600 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-300 transition max-md:px-5 max-md:mt-10"
          aria-label="Read more about font pairs guide"
        >
          Read More &gt;
        </button>
      </div>

      <!-- Background image -->
      <div class="absolute inset-0 w-full h-full">
        <img 
          loading="lazy" 
          src="@/assets/images/misc/cover.png" 
          alt="Background image for step-by-step guide article"
          class="object-cover w-full h-full"
          style="object-position: center right;"  
        />
      </div>

      <!-- Overlay to darken the image and highlight the text -->
      <div class="absolute inset-0 bg-black opacity-40"></div>
    </article>
    <!-- Sections Wrapper for Consistent Margins -->
    <div class="mx-auto max-w-7xl px-8">

      <!-- Featured Posts Section -->
      <div class="mb-8">
        <featuredPost />
      </div>

      <!-- About Us and Mission Section -->
      <section data-layername="aboutUsOurMission" class="flex flex-col mb-8">
        <img loading="lazy" src="/assets/pattern.jpg" alt="Background pattern" class="object-contain self-end aspect-[45.45] max-w-[1061px] w-[1061px] max-md:max-w-full" />
        <section class="bg-gray-100 py-24 px-8 mt-2 max-md:px-5">
          <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
            <!-- Column: About Us -->
            <article>
              <h2 class="uppercase text-gray-500 font-bold text-sm tracking-widest">About Us</h2>
              <h3 class="mt-4 text-4xl font-bold text-gray-900 leading-snug">
                We are a community of content writers who share their learnings
              </h3>
              <p class="mt-4 text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
              </p>
              <a href="#" class="mt-6 text-yellow-500 font-bold inline-block hover:text-yellow-600 focus:text-yellow-600 focus:outline-none transition">
                Read More &gt;
              </a>
            </article>

            <!-- Column: Our Mission -->
            <article>
              <h2 class="uppercase text-gray-500 font-bold text-sm tracking-widest">Our Mission</h2>
              <h3 class="mt-4 text-4xl font-bold text-gray-900 leading-snug">
                Creating valuable content for creatives all around the world
              </h3>
              <p class="mt-4 text-gray-600">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
              </p>
            </article>
          </div>
        </section>
      </section>
 <!-- Additional Components -->
      <div class="mb-8">
        <Category />
      </div>

      <div class="mb-8">
        <SpecialPost />
      </div>

     
      <div class="mb-8">
        <list />
      </div>
      <div class="mb-8">
        <testi />
      </div>
      <div class="mb-8">
        <JoinTeam />
      </div>
    </div>
  </MainLayout>
</template>

<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue';
import featuredPost from '@/components/HomePage/featuredPost.vue';
import Category from '@/components/HomePage/Category.vue';
import list from '@/components/HomePage/list.vue';
import testi from '@/components/HomePage/testi.vue';
import SpecialPost from '@/components/HomePage/Special.vue';
import JoinTeam from '@/components/JoinTeam.vue';
</script>
