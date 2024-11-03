<script setup lang="ts">
</script>

<template>
  <section class="flex flex-col items-center mt-32 max-md:mt-10">
    <h1 class="text-base font-black leading-none text-center text-gray-800 uppercase tracking-[3px]">Contact us</h1>
    <h2 class="mt-3 text-5xl font-bold tracking-tighter leading-none text-center text-gray-800 max-md:max-w-full max-md:text-4xl">
      Let's Start a Conversation
    </h2>
    <p class="mt-6 text-base leading-7 text-center text-zinc-500 w-[768px] max-md:max-w-full">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.
    </p>
  </section>

  <section class="px-16 py-12 mt-16 max-w-full bg-amber-300 w-[768px] mx-auto max-md:px-5 max-md:mt-10">
    <div class="flex gap-5 max-md:flex-col">
      <article class="flex flex-col w-6/12 max-md:ml-0 max-md:w-full">
        <div class="flex flex-col grow items-start text-xl leading-relaxed text-neutral-600 max-md:mt-10">
          <h3 class="text-sm leading-none opacity-60">Working hours</h3>
          <hr class="shrink-0 self-stretch mt-4 h-px border border-solid opacity-10 bg-neutral-600 border-neutral-600" />
          <p class="mt-4 font-bold">Monday To Friday</p>
          <p class="font-bold">9:00 AM to 8:00 PM</p>
          <p class="text-base leading-7 opacity-60">Our Support Team is available 24/7</p>
        </div>
      </article>
      <article class="flex flex-col ml-5 w-6/12 max-md:ml-0 max-md:w-full">
        <div class="flex flex-col items-start text-neutral-600 max-md:mt-10">
          <h3 class="text-sm leading-none opacity-60">Contact Us</h3>
          <hr class="shrink-0 self-stretch mt-4 h-px border border-solid opacity-10 bg-neutral-600 border-neutral-600" />
          <p class="mt-4 text-xl font-bold leading-relaxed">020 7993 2905</p>
          <p class="text-base leading-7 opacity-60">hello@finsweet.com</p>
        </div>
      </article>
    </div>
  </section>

  <!-- Form Section -->
  <section class="px-16 py-12 mt-10 max-w-full bg-white w-[768px] mx-auto max-md:px-5">
    <form class="flex flex-col gap-6">
      <div class="flex flex-col">
        <label class="text-sm font-medium text-neutral-600">Full Name</label>
        <input type="text" class="mt-2 p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-800" />
      </div>

      <div class="flex flex-col">
        <label class="text-sm font-medium text-neutral-600">Your Email</label>
        <input type="email" class="mt-2 p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-800" />
      </div>

      <div class="flex gap-6">
        <div class="flex flex-col w-1/2">
          <label class="text-sm font-medium text-neutral-600">Province</label>
          <select class="mt-2 p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-800">
            <option>Select Province</option>
            <!-- Options can be populated here -->
          </select>
        </div>

        <div class="flex flex-col w-1/2">
          <label class="text-sm font-medium text-neutral-600">City</label>
          <select class="mt-2 p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-800">
            <option>Select City</option>
            <!-- Options can be populated here -->
          </select>
        </div>
      </div>

      <div class="flex flex-col">
        <label class="text-sm font-medium text-neutral-600">Message</label>
        <textarea rows="4" class="mt-2 p-3 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-blue-800"></textarea>
      </div>

      <!-- Send Message Button with Blue Color -->
      <button type="submit" class="mt-4 py-3 px-6 bg-blue-800 text-white font-bold rounded-md hover:bg-blue-900 focus:outline-none focus:ring-2 focus:ring-blue-900">
        Send Message
      </button>
    </form>
  </section>
</template>