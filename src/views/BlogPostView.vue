<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import HeaderBlog from '@/components/BlogPost/HeaderBlog.vue';
import imageBlog from '@/components/BlogPost/imageBlog.vue';
import BlogContent from '@/components/BlogPost/BlogContent.vue';
import BlogPostSectionnn from '@/components/BlogPost/BlogPostSectionnn.vue';
import JoinTeam from '@/components/JoinTeam.vue';
</script>

<template>
  <MainLayout>
      <HeaderBlog/>
      <imageBlog/>
      <BlogContent/>
      <BlogPostSectionnn/>
      <div class="mb-8">
        <JoinTeam />
      </div>
  </MainLayout>
</template>
