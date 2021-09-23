<template>
  <section class="proyectos h-screen">
    <div class="proyectos__title">
      <p>Participaciones</p>
    </div>
    <div class="proyectos__contenedor flex flex-wrap">
      <div class="bg-azul h-200 w-200">Gii Studio</div>
      <div class="bg-azul h-200 w-200">Amazon</div>
      <div class="bg-azul h-200 w-200">Gii Studio</div>
      <div class="bg-azul h-200 w-200">Amazon</div>
      <div class="bg-azul h-200 w-200">Gii Studio</div>
      <div class="bg-azul h-200 w-200">Amazon</div>
    </div>
  </section>
</template>
<style lang="scss">
.proyectos {
  &__title {
    font-size: 2rem;
  }
  &__contenedor {
    grid-auto-columns: auto;
  }
}
</style>
