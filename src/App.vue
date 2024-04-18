<script setup lang="ts">
import profileImage from './assets/profile.jpeg';
</script>

<template>
  <main class="py-6 px-4 sm:p-6 md:py-10 md:px-8 bg-blue-100 dark:bg-blue-900">
    <h1 class="mt-1 text-2xl font-semibold text-gray-900 dark:text-white">POLITEKNIK BRUNEI</h1>
    <div class="mt-6 flex flex-col sm:flex-row">
      <div class="w-full sm:w-1/2">
        <img :src="profileImage" alt="Profile Image" class="w-full h-auto rounded-lg shadow-md lg:col-1"/>
      </div>
      <div class="w-full sm:w-1/2 mt-4 sm:mt-0 p-6">
        <h2 class="text-lg font-semibold text-gray-900 dark:text-white">RAHIMI AFIQ HASYIR</h2>
        <div class="mt-4 bg-red-100 dark:bg-red-800 p-6 rounded-lg shadow-md">
          <div class="text-base leading-6 text-gray-700 dark:text-gray-300 flex flex-col lg:flex-row">
            <p class="flex-grow lg:col-2 text-center" >
              My name is Awang Mohd Nur Rahimi Afiq Hasyir Bin Awang Haji Ismail. I'm 23 years old and currently a student at Politeknik Brunei, pursuing a Diploma in Web Development. I have a passion for technology, enjoy playing mobile games, handball, and watching movies. I'm always eager to learn new things.
            </p>
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<style scoped>
</style>
