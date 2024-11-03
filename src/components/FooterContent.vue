<template>
  <footer class="flex overflow-hidden flex-col justify-center px-20 py-14 bg-gray-800 max-md:px-5">
    <!-- Top section with logo and navigation -->
    <div class="flex flex-wrap gap-5 justify-between items-start w-full text-base leading-7 text-white max-md:max-w-full">
      <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/751ab37168ee156d9ebddc205ceda1e31f35ca7e214188d7b69f392ad83c7019?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" alt="Company Logo" class="object-contain shrink-0 max-w-full aspect-[5] w-[140px]" />
      <nav class="flex gap-6">
        <a href="/home" class="grow">Home</a>
        <a href="/blogg">Blog</a>
        <a href="/about" class="my-auto leading-loose">About us</a>
        <a href="/contact">Contact us</a>
        <a href="/privacy" class="basis-auto">Privacy Policy</a>
      </nav>
    </div>

    <!-- Newsletter section -->
    <section class="px-16 py-20 mt-14 w-full bg-white bg-opacity-10 max-md:px-5 max-md:mt-10 max-md:max-w-full">
      <div class="flex gap-5 max-md:flex-col">
        <div class="flex flex-col w-6/12 max-md:ml-0 max-md:w-full">
          <h2 class="text-4xl font-bold tracking-tighter leading-10 text-white max-md:mt-10 max-md:max-w-full">
            Subscribe to our newsletter to get latest updates and news
          </h2>
        </div>
        <div class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
          <!-- Updated input and button as per new design -->
          <form class="flex items-center gap-4">
            <label for="emailInput" class="sr-only">Enter Your Email</label>
            <input 
              type="email" 
              id="emailInput"
              placeholder="Enter Your Email"
              class="px-4 py-2 text-base border border-gray-400 bg-transparent text-white placeholder-gray-400 focus:outline-none focus:ring-2 focus:ring-blue-500 w-[250px]"
              required
            />
            <button 
              type="submit"
              class="px-6 py-2 text-base font-semibold text-white bg-blue-600 rounded-md hover:bg-blue-700 focus:outline-none focus:ring-2 focus:ring-blue-500"
            >
              Subscribe
            </button>
          </form>
        </div>
      </div>
    </section>

    <!-- Contact information and social media links -->
    <div class="flex flex-wrap gap-5 justify-between mt-12 text-base leading-7 text-white max-md:mt-10 max-md:max-w-full">
      <address class="opacity-70 not-italic">
        Finstreet 118 2561 Fintown
      </address>
      <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/89c171f66cfa5f1ef47b72867b2d75513a839003797daa019deea9e365e9709f?placeholderIfAbsent=true&apiKey=78d47c82a12c424c9949a4600f8ca792" alt="Company Social Media Links" class="object-contain shrink-0 self-start mt-3 w-36 max-w-full aspect-[9.01]" />
    </div>

    <!-- Additional contact links (email and phone number) -->
    <address class="self-start text-base leading-7 text-white opacity-70 not-italic">
      <a href="mailto:Hello@finsweet.com">Hello@finsweet.com</a>
      <a href="tel:02079932905">020 7993 2905</a>
    </address>
  </footer>
</template>

<style scoped>
builder-component {
  max-width: none !important;
}
</style>
