<template>
  <div class="flex flex-col h-screen">
    <header class="flex items-center h-14 px-4 border-b border-gray-300 sm:h-16 md:px-6 lg:px-8">
      <div>
        <a class="flex items-center gap-2 font-semibold" href="#">
          <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="40" height="40" />
        </a>
      </div>
      <nav class="ml-auto space-x-4 flex items-center h-10 sm:space-x-6">
        <RouterLink :to="{ name: 'home' }">Início</RouterLink>
        <RouterLink to="/features">Diferenciais</RouterLink>
        <RouterLink to="/pricing">Preços</RouterLink>
        <RouterLink to="/contact">Contato</RouterLink>
        <RouterLink to="/auth">Login</RouterLink>
      </nav>
    </header>

    <main class="flex-1 flex items-center justify-center">
      <RouterView />
    </main>

    <footer class="flex items-center h-14 px-4 border-t border-gray-300 sm:h-16 md:px-6 lg:px-8">
      <p class="flex-1 text-sm text-gray-500 text-center">
        © {{ currentYear }} Capsule Corporation. Todos os direitos reservados
      </p>
    </footer>
  </div>
</template>

<script setup lang="ts">
const currentYear = new Date().getFullYear()
</script>
