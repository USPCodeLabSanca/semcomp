<template>
  <div id="objectives" class="bg-secondary text-white py-16">
    <div class="container mx-auto flex items-center justify-center md:justify-between w-full">
      <div class="flex flex-wrap items-stretch">
        <div class="w-full md:w-1/3 text-center px-8">
          <h2 class="text-5xl">
            680
          </h2>
          <p>participantes</p>
        </div>

        <div class="w-full md:w-1/3 text-center px-8">
          <h2 class="text-5xl">
            8
          </h2>
          <p>dias de programação (Hackathon, Game Jam, palestras, minicursos, eventos culturais, concursos e muito mais!)</p>
        </div>

        <div class="w-full md:w-1/3 text-center px-8">
          <h2 class="text-5xl">
            16
          </h2>
          <p>patrocinadores</p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.card {
  height: 100%;
  background-color: #ffffff;
}

.resize {
  box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.25);
  transition: transform 500ms cubic-bezier(0.215, 0.61, 0.355, 1);
}

.resize:hover {
  transform: scale(1.025);
}

@media (min-width: 576px) {
  .resize:hover {
    transform: scale(1.05);
  }
}
</style>
