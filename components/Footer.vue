<template>
  <div class="bg-secondary py-6">
    <div
      class="container mx-auto flex flex-col-reverse md:flex-row items-center justify-center md:justify-between h-full"
    >
      <div class="text-center text-white md:text-left px-4 flex flex-col-reverse md:flex-row items-center">
        <div>
          <img class="icon p-2 mx-2 shadow-md" src="/logo.svg" alt="Semcomp Logo">
        </div>
        <div>
          <div class="mt-4 w-full flex md:block justify-center">
            <img src="/logo-text.svg" alt="Kiwi standing on oval">
          </div>
          <p class="mb-4 text-xl">
            A melhor semana acadêmica de computação do Brasil
          </p>
        </div>
      </div>
      <div class="px-4 flex">
        <a href="https://pt-br.facebook.com/Semcomp/" target="_blank" rel="noopener noreferrer">
          <div class="icon-s p-2 mx-2 shadow-md">
            <img src="/icon-1.svg" alt="Facebook">
          </div>
        </a>
        <a href="https://www.instagram.com/semcomp/" target="_blank" rel="noopener noreferrer">
          <div class="icon-s p-2 mx-2 shadow-md">
            <img src="/icon-2.svg" alt="Instagram">
          </div>
        </a>
      </div>
    </div>
  </div>
</template>

<style scoped>
.icon {
  width: auto;
  background-color: white;
  border-radius: 100%;
  height: 100px;
}

.icon-s {
  width: 50px;
  background-color: white;
  border-radius: 100%;
}
</style>
