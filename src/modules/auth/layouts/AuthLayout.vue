<template>
  <div class="bg-gray-100 flex justify-center items-center h-screen">
    <div class="w-1/2 h-screen hidden lg:block">
      <img
        src="https://images.pexels.com/photos/28396251/pexels-photo-28396251.jpeg"
        alt="Imagem de Login"
        class="object-cover w-full h-full"
      />
    </div>
    <div class="lg:p-36 md:p-52 sm:20 p-8 w-full lg:w-1/2">
      <RouterView />
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
