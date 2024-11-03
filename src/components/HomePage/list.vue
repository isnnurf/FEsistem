<template>
    <section class="flex flex-col gap-10 items-center text-zinc-500">
      <!-- List of Authors Section -->
      <h1 class="self-center text-4xl font-bold tracking-tighter leading-none text-gray-800">
        List of Authors
      </h1>
      <main class="mt-12 w-full max-md:mt-10 max-md:max-w-full">
        <div class="flex gap-10 justify-center max-md:flex-col">
          <article v-for="author in authors" :key="author.id" class="flex flex-col w-1/5 items-center max-md:ml-0 max-md:w-full">
            <div :class="['flex flex-col grow items-center px-6 py-8 w-full leading-none max-md:px-5 max-md:mt-8 rounded-lg', author.bgColor]">
              <img :src="author.image" :alt="author.name" loading="lazy" class="object-contain w-24 h-24 max-w-full rounded-full aspect-square" />
              <h2 class="mt-5 text-xl font-bold tracking-tighter text-gray-800">
                {{ author.name }}
              </h2>
              <p class="self-stretch text-sm text-center text-zinc-500">
                Content Writer @Company
              </p>
              <div class="flex gap-2 mt-3">
                <a v-for="(icon, index) in author.socialIcons" :key="index" :href="icon.link" class="text-gray-500">
                  <img :src="icon.iconSrc" class="w-5 h-5" alt="Social Icon" />
                </a>
              </div>
            </div>
          </article>
        </div>
      </main>
  
      <!-- Logo Section -->
      <section data-layername="logoComponent" class="flex flex-wrap gap-10 items-start text-zinc-500" aria-labelledby="featured-section-title">
    <header class="flex flex-col self-start mt-0">
      <h2 id="featured-section-title">
        <span class="self-start text-sm leading-none opacity-60">We are</span>
        <span class="block text-2xl font-bold leading-none">Featured in</span>
      </h2>
    </header>
    <img 
      loading="lazy" 
      src="https://cdn.builder.io/api/v1/image/assets/TEMP/4423d4f8991ccfa21577df9ae7b50e9b509e52e49d996e0e7f1d48cd67173bf3?placeholderIfAbsent=true&apiKey=f3c3b267233b466aa7f8a88a8d8927de" 
      alt="Featured publications and partners logos"
      class="object-contain grow shrink-0 my-auto aspect-[31.25] basis-0 w-fit max-md:max-w-full" 
    />
  </section>
    </section>
  </template>
  
  <script>
  export default {
    name: 'LogoAndAuthors',
    data() {
      return {
        authors: [
          {
            id: 1,
            name: 'Floyd Miles',
            image: 'https://cdn.builder.io/api/v1/image/assets/TEMP/cbb5b48e8a0e3435ce4903b4895eb803d0ff99360b8dbd5238033ee86b332802?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2',
            socialIcons: [
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733547.png', link: '#' }, // Facebook
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733558.png', link: '#' }, // Twitter
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733579.png', link: '#' }, // Instagram
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733561.png', link: '#' }, // LinkedIn
            ],
            bgColor: 'bg-zinc-100'
          },
          {
            id: 2,
            name: 'Dianne Russell',
            image: 'https://cdn.builder.io/api/v1/image/assets/TEMP/df167acd41ee793d00ba35e2ce34c50c5f652c16adcdf7949de617bea0c833ca?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2',
            socialIcons: [
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733547.png', link: '#' }, // Facebook
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733558.png', link: '#' }, // Twitter
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733579.png', link: '#' }, // Instagram
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733561.png', link: '#' }, // LinkedIn
            ],
            bgColor: 'bg-orange-50'
          },
          {
            id: 3,
            name: 'Jenny Wilson',
            image: 'https://cdn.builder.io/api/v1/image/assets/TEMP/17128d3f16192b6d9a2897ed55c2dd5653847191b32aede0d5eb2b2981001a2b?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2',
            socialIcons: [
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733547.png', link: '#' }, // Facebook
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733558.png', link: '#' }, // Twitter
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733579.png', link: '#' }, // Instagram
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733561.png', link: '#' }, // LinkedIn
            ],
            bgColor: 'bg-zinc-100'
          },
          {
            id: 4,
            name: 'Leslie Alexander',
            image: 'https://cdn.builder.io/api/v1/image/assets/TEMP/49588a299ec37a02269b93840924e68c1cf9ceeff427886f687287c7b8ea0531?placeholderIfAbsent=true&apiKey=c8698c43222e44c9baf2ff8bdf6a77c2',
            socialIcons: [
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733547.png', link: '#' }, // Facebook
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733558.png', link: '#' }, // Twitter
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733579.png', link: '#' }, // Instagram
              { iconSrc: 'https://cdn-icons-png.flaticon.com/512/733/733561.png', link: '#' }, // LinkedIn
            ],
            bgColor: 'bg-zinc-100'
          }
        ],
        logos: [
          { id: 1, src: 'https://dummyimage.com/100x50/000/fff&text=logoipsum1' },
          { id: 2, src: 'https://dummyimage.com/100x50/000/fff&text=logoipsum2' },
          { id: 3, src: 'https://dummyimage.com/100x50/000/fff&text=logoipsum3' },
          { id: 4, src: 'https://dummyimage.com/100x50/000/fff&text=logoipsum4' },
          { id: 5, src: 'https://dummyimage.com/100x50/000/fff&text=logoipsum5' }
        ]
      }
    }
  }
  </script>
  
  <style scoped>
  .builder-component {
    max-width: none !important;
  }
  </style>
  