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
      <h1 class="text-2xl font-semibold mb-4">Entrar</h1>
      <form action="#" method="POST">
        <div class="mb-4">
          <label for="username" class="block text-gray-600">Nome de Usuário</label>
          <input
            type="text"
            id="username"
            name="username"
            class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:border-blue-500"
            autocomplete="off"
          />
        </div>
        <div class="mb-4">
          <label for="password" class="block text-gray-600">Senha</label>
          <input
            type="password"
            id="password"
            name="password"
            class="w-full border border-gray-300 rounded-md py-2 px-3 focus:outline-none focus:border-blue-500"
            autocomplete="off"
          />
        </div>
        <div class="mb-4 flex items-center">
          <input type="checkbox" id="remember" name="remember" class="text-blue-500" />
          <label for="remember" class="text-gray-600 ml-2">Lembrar de mim</label>
        </div>
        <div class="mb-6 text-blue-500">
          <a href="#" class="hover:underline">Esqueceu a senha?</a>
        </div>
        <button
          type="submit"
          class="bg-blue-500 hover:bg-blue-600 text-white font-semibold rounded-md py-2 px-4 w-full"
        >
          Entrar
        </button>
      </form>
      <div class="mt-6 text-blue-500 text-center">
        <a href="#" class="hover:underline">Cadastre-se aqui</a>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts"></script>

<style scoped></style>
