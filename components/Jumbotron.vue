<template>
  <div id="subscribe" class="bg-primary text-white">
    <div class="svg-maneirissimo">
      <div
        class="container mx-auto flex flex-col md:flex-row w-full items-center justify-center md:justify-between h-full"
      >
        <object
          data="/logo.svg"
          alt="DeepHack Logo"
          class="logo mx-4"
        />

        <div class="text-center justify-center md:text-left md:justify-left px-4 w-full">
          <div>
            <object
              data="/logo-text.svg"
              alt="DeepHack Logo"
              class="icon-text relative"
            />
          </div>
          <span class="py-4">
            Dias 28 de Setembro à 04 de Outubro de 2019
          </span>
          <h2 class="subtitle2 py-4">
            A melhor semana acadêmica de computação do Brasil
          </h2>
          <div class="py-4">
            <button
              class="text-gray-500 py-2 px-4 border border-gray-500 rounded cursor-default"
            >
              Inscreva-se
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.svg-maneirissimo {
  height: 100vh;
}

.logo {
  width: 100%;
  max-width: 300px;
}

.logo-text {
  max-width: 100%;
}
</style>
