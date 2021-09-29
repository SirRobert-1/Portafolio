<template>
  <section class="proyectos h-screen">
    <div class="proyectos__title">
      <p>Participaciones</p>
    </div>
    <div class="proyectos__contenedor flex flex-wrap">
      <div class="bg-transparent border-2 h-250 w-250">Gii Studio</div>
      <div class="bg-transparent border-2 h-250 w-250">Amazon</div>
      <div class="bg-transparent border-2 h-250 w-250">Gii Studio</div>
      <div class="bg-transparent border-2 h-250 w-250">Amazon</div>
      <div class="bg-transparent border-2 h-250 w-250">Gii Studio</div>
      <div class="bg-transparent border-2 h-250 w-250">Amazon</div>
    </div>
  </section>
</template>
<style lang="scss">
.proyectos {
  &__title {
    font-size: 2rem;
  }
  &__contenedor {
    display: grid;
    grid-template-columns: 250px 250px 250px 250px;
    grid-template-rows: 250px 250px;
    row-gap: 20px;
    column-gap: 40px;
    margin: 40px 80px;
    text-align: center;
    overflow-x: auto;
  }
}
</style>
