<template>
    <section data-layername="blogCategoryHero" class="flex flex-col text-base text-center text-gray-800">
      <header data-layername="background" class="flex flex-col justify-center items-center p-20 w-full bg-gray-100 max-md:px-5 max-md:max-w-full">
        <div class="flex flex-col items-center max-w-full w-[472px]">
          <h1 data-layername="business" class="text-6xl font-bold tracking-tighter leading-none max-md:text-4xl">
            Business
          </h1>
          <p data-layername="loremIpsumDolorSitAmetConsecteturAdipiscingElitSedDoEiusmodTemporIncididuntUtLabore" class="self-stretch mt-4 leading-7 text-zinc-500 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore.
          </p>
          <nav data-layername="blogBusiness" class="mt-8 font-medium leading-none uppercase tracking-[3px]" aria-label="breadcrumb">
            <a href="/blog" class="hover:underline focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500">Blog</a>
            <span aria-hidden="true"> &gt; </span>
            <a href="/blog/business" class="hover:underline focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-blue-500" aria-current="page">Business</a>
          </nav>
        </div>
      </header>
    </section>
  </template>
  
  <style scoped>
  builder-component {
    max-width: none !important;
  }
  </style>