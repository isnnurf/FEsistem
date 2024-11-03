<script setup lang="ts">
interface CategoryCardProps {
  title: string;
  description: string;
  iconSrc: string;
  isHighlighted?: boolean;
  link: string; // Add link property
}

const props = defineProps<CategoryCardProps>();
</script>

<template>
  <router-link :to="props.link" class="flex flex-col w-3/12 max-md:ml-0 max-md:w-full">
    <div 
      :class="[ 
        'flex flex-col grow items-start p-8 w-full border border-solid transition-colors duration-300',
        props.isHighlighted ? 'bg-blue-600' : 'border-zinc-500',
        'max-md:px-5 max-md:mt-8',
        { 
          'hover:bg-blue-600 hover:border-transparent': !props.isHighlighted, 
          'hover:text-white': !props.isHighlighted 
        } 
      ]"
    >
      <img 
        :src="props.iconSrc" 
        :alt="`${props.title} category icon`" 
        class="object-contain w-12 aspect-square transition-transform duration-300 hover:scale-110" 
      />
      <h3 
        :class="[ 
          'mt-4 text-3xl font-bold tracking-tighter leading-none transition-colors duration-300',
          props.isHighlighted ? 'text-orange-50' : 'text-gray-800',
          { 'hover:text-white': !props.isHighlighted } 
        ]"
      >
        {{ props.title }}
      </h3>
      <p 
        :class="[ 
          'self-stretch mt-1 text-base leading-7 transition-colors duration-300',
          props.isHighlighted ? 'text-white' : 'text-zinc-500',
          { 'hover:text-white': !props.isHighlighted } 
        ]"
      >
        {{ props.description }}
      </p>
    </div>
  </router-link> 
</template>
