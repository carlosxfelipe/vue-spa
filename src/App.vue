<script setup lang="ts">
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
</script>

<template>
  <header
    class="flex flex-col items-center gap-8 py-8 md:flex-row md:items-center md:justify-start md:gap-8 md:pr-8"
  >
    <img
      alt="Vue logo"
      src="./assets/logo.svg"
      width="125"
      height="125"
      class="block mx-auto md:mx-0"
    />

    <div class="flex flex-col items-start flex-wrap">
      <HelloWorld msg="You did it!" />
    </div>
  </header>

  <main>
    <TheWelcome />
  </main>
</template>
