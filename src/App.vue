<script setup lang="ts">
import profileImage from './assets/profile.jpeg';
</script>


<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8">
    <h1 class="mt-1 text-lg font-semibold text-white sm:text-slate-900 md:text-2xl dark:sm:text-white">PROFILE PAGE </h1>
        <img :src="profileImage" alt="" class="w-full h-full object-cover rounded-lg sm:h-100 sm:col-span-2 lg:col-span-full" loading="lazy">
      <p class="mt-4 text-sm leading-6 col-start-1 sm:col-span-2 lg:mt-6 lg:row-start-4 lg:col-span-1 dark:text-slate-400">
        This sunny and spacious room is for those traveling light and looking for a comfy and cosy place to lay their head for a night or two. This beach house sits in a vibrant neighborhood littered with cafes, pubs, restaurants and supermarkets and is close to all the major attractions such as Edinburgh Castle and Arthur's Seat.
      </p>
  </main>
</template>

<style scoped>
</style>
