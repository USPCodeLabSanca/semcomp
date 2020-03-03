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
          <p class="mt-4 text-3xl">
            Semcomp
          </p>
          <p class="mb-4 text-xl">
            A melhor semana acadêmica de computação do Brasil
          </p>
        </div>
      </div>
      <div class="px-4 flex">
        <a href="https://pt-br.facebook.com/Semcomp/" target="_blank" rel="noopener noreferrer">
          <img class="icon icon-social p-2 mx-2 shadow-md" src="/facebookk.svg" alt="Facebook">
        </a>
        <a href="https://www.instagram.com/semcomp/" target="_blank" rel="noopener noreferrer">
          <img class="icon icon-social p-2 mx-2 shadow-md" src="/instagramm.svg" alt="Instagram">
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

.icon-social {
  height: 50px;
}
</style>
