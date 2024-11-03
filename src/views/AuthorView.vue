<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import author from '@/components/AuthorPage/authorHeader.vue';
import BlogPost from '@/components/AuthorPage/BlogPost.vue';
</script>

<template>
  <MainLayout>
      <author/>
    <BlogPost/>
  </MainLayout>
</template>