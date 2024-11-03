<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
import FeaturedPost from '@/components/Blog/FeaturedPost.vue'
import AllPost from '@/components/Blog/BlogPost.vue'
import CategorySection from '@/components/Blog/CategorySection.vue'
import SpecialPost from '@/components/Blog/SpecialPost.vue'
import JoinTeam from '@/components/JoinTeam.vue'


</script>

<template>
  <MainLayout>
    <FeaturedPost>
    </FeaturedPost>
    <AllPost category="News" title="Some title" description="Some description" />
    <CategorySection>
    </CategorySection>
    <SpecialPost/>
    <div class="mb-8">
        <JoinTeam />
      </div>
  </MainLayout>
</template>

<script lang="ts">
import {
  defineComponent
} from 'vue'

export default defineComponent({
  name: 'BlogLayout'
})

</script>

<style scoped>

</style>
