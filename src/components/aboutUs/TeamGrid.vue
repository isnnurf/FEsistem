<script setup lang="ts">
import TeamMember from './TeamMember.vue';

const teamMembers = [
  {
    name: 'Guy Hawkins',
    role: 'Content Writer @Company',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/89e9cd620871b328c84c60f933686e698169cc62e471800ebf80498763adc9f3?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    ratingImageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/0bf578f41bfc1f1d64bcb84f6cdf4af5ca49b3b369cd1cabf2c9555fa5178425?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c'
  },
  {
    name: 'Eleanor Pena',
    role: 'Content Writer @Company',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/48cec530a46ec7e0ffcfdced1155b13d3454f9e8c9e9ac190e85822948127d30?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    ratingImageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/d988082c397f5218633fed7d0d13f1f4cd82cc02bc92e16252e3481ecac11b4e?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c'
  },
  {
    name: 'Robert Fox',
    role: 'Content Writer @Company',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/81bf49d815710eda179f1e9c6001331a9e21a21f2746ed0447604362101188fe?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    ratingImageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/24886fb0cde1baf271a8c7277e6dc9f1c9b54e712f55b34247f6713752becee1?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c'
  },
  {
    name: 'Jacob Jones',
    role: 'Content Writer @Company',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/14208b7976a6fdce9b1b9a8c8c46911b88a88ea478efc5ce8bc9b13e80ed1615?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    ratingImageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/33b59c84cd22e4f2b5f6b27bba717ad0c254cba3555f2d6f121ae285a25dda13?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c'
  },
  {
    name: 'Floyd Miles',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/9a08ac807213d9627fd7596c3e46ac3eb0e08d4f8417cb8b287915d18f59c9b0?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/1238ee317e4d950c47462a8781004569222f5063d18c62b46045be59f5d09f0c?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
  },
  {
    name: 'Dianne Russell',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/e22bc8df8cd660950385732d863cfe8a46f88897df05f7505ee7e97e51005442?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/1c9c48561b3186ae70f6b970405961d5a9c6b9c43d66ee11aa828ca3c0998ca7?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    highlighted: true,
  },
  {
    name: 'Jenny Wilson',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/431ba0a554f76db4c1d3c76b098c205bdd0514c081424011e52b03ec1dacf10c?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/a13c20e02307566ec9ee2b01a8a4f6d466967e040965c02f5c5b1d0a316693b4?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
  },
  {
    name: 'Leslie Alexander',
    imageSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/54d3f7ddccbe68495e8eb4e094d3be6ca1098fc5100fa4f626206f477da5cb8f?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
    starsSrc: 'https://cdn.builder.io/api/v1/image/assets/TEMP/1ac3ed92c6ed50224ad7d84b082f37c1045a93a8a7b7ef12a47acc2d919e1592?placeholderIfAbsent=true&apiKey=79875f50433f4dddb865cc88bfb43a5c',
  },
];
</script>

<template>
  <section class="flex justify-center items-center min-h-screen bg-gray-100 px-8 py-20">
    <div class="w-full max-w-[1400px] text-center">
      <h4 class="text-6xl font-extrabold tracking-tight leading-tight text-gray-800 max-md:text-5xl">List Of Authors</h4>
      <div class="grid grid-cols-4 gap-8 mt-12 max-md:grid-cols-1">
        <router-link
          v-for="member in teamMembers"
          :key="member.name"
          to="/AuthorView"
          class="flex flex-col hover:shadow-lg transition duration-150 ease-in-out"
        >
          <TeamMember v-bind="member" />
        </router-link>
      </div>
    </div>
  </section>
</template>

