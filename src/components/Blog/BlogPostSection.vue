<template>
  <section class="blog-post-section">
    <h2 class="self-start uppercase tracking-[3px]">{{ category }}</h2>
    <h3 class="mt-5 mr-6 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:mr-2.5 max-md:max-w-full">
      {{ title }}
    </h3>
    <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
      {{ description }}
    </p>
  </section>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'BlogPostSection',
  props: {
    category: {
      type: String,
      required: true
    },
    title: {
      type: String,
      required: true
    },
    description: {
      type: String,
      required: true
    }
  }
})
</script>

<style scoped>
.blog-post-section {
  margin-top: 11rem;
}
.blog-post-section:first-child {
  margin-top: 0;
}
@media (max-width: 768px) {
  .blog-post-section {
    margin-top: 2.5rem;
  }
}
</style>
