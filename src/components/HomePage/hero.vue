<template>
    <article data-layername="homeHero" class="flex flex-col text-base font-bold text-white">
      <section class="flex relative flex-col w-full min-h-[720px] max-md:max-w-full">
        <img 
          loading="lazy" 
          src="https://cdn.builder.io/api/v1/image/assets/TEMP/ebd6e688cd9cb7393db315b136df4921bbb1100ddb71d1791b74073fba2bad83?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" 
          alt="Background image for step-by-step guide article"
          class="object-cover absolute inset-0 size-full"
        />
        <div 
          data-layername="overlay" 
          class="flex relative flex-col items-start px-20 py-40 w-full max-md:px-5 max-md:py-24 max-md:max-w-full"
        >
          <header 
            data-layername="postedOnStartup" 
            class="font-semibold leading-none uppercase tracking-[3px]"
          >
            <span class="font-medium">Posted on</span>
            <strong class="font-black">startup</strong>
          </header>
          <h1 
            data-layername="stepByStepGuideToChoosingGreatFontPairs" 
            class="mt-6 text-6xl tracking-tighter leading-[64px] w-[803px] max-md:max-w-full max-md:text-4xl max-md:leading-[51px]"
          >
            Step-by-step guide to choosing great font pairs
          </h1>
          <p 
            data-layername="byJamesWestMay232022" 
            class="mt-6 leading-7 text-blue-600"
          >
            By <span class="text-blue-600">James West</span> | <time datetime="2022-05-23">May 23, 2022</time>
          </p>
          <p 
            data-layername="duisAuteIrureDolorInReprehenderitInVoluptateVelitEsseCillumDoloreEuFugiatNullaPariaturExcepteurSintOccaecatCupidatatNonProident" 
            class="mt-4 leading-7 w-[599px] max-md:max-w-full"
          >
            Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident.
          </p>
          <button 
            data-layername="button"
            class="gap-3 px-12 py-4 mt-12 mb-0 text-lg leading-none bg-blue-600 max-md:px-5 max-md:mt-10 max-md:mb-2.5"
            aria-label="Read more about font pairs guide"
          >
            Read More &gt;
          </button>
        </div>
      </section>
    </article>
  </template>
  
  <style scoped>
  builder-component {
    max-width: none !important;
  }
  </style>