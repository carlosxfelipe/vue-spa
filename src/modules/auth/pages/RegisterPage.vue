<template>
  <h1 class="text-2xl font-semibold mb-4">Registro</h1>
  <form action="#" method="POST">
    <div class="mb-4">
      <label for="name" class="block text-gray-600">Nome de Usuário</label>
      <input
        type="text"
        id="name"
        name="name"
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
      Registrar
    </button>
  </form>
  <div class="mt-6 text-blue-500 text-center">
    <RouterLink :to="{ name: 'login' }" class="hover:underline"
      >Já tem uma conta? Entrar
    </RouterLink>
  </div>
</template>
