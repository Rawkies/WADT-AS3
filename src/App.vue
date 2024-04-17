<script setup lang="ts">
import profileImage from './assets/profile.jpeg';
</script>


<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8">
    <h1 class="mt-1 text-lg font-semibold text-white sm:text-slate-900 md:text-2xl dark:sm:text-white">PROFILE PAGE </h1>
        <img :src="profileImage" alt="" class="w-full h-full object-cover rounded-lg sm:h-100 sm:col-span-2 lg:col-span-full" loading="lazy">
    <div>
    <p class="text-sm leading-4 font-medium text-white sm:text-slate-500 dark:sm:text-slate-400">RAHIMI AFIQ HASYIR</p>
      <p class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400">
        My Name Awang Mohd Nur Rahimi AFiq Hasyir Bin Awang Haji ismail, im 23 year old. love to play mobile games, handball and also love to watch movies. I am also a student at Politeknik Brunei, currently studying in Diploma in WEB DEVELOPER. I am a person who is very interested in the world of technology and I am very interested in learning new things. 
      </p>
    </div> 
  </main>
</template> 

<style scoped>
</style>
