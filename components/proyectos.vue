<template>
  <section class="proyectos xs:h-full lg:h-screen bg-beige">
    <div class="proyectos__title pl-5">
      <p>Participaciones</p>
    </div>
    <div class="proyectos__contenedor">
      <div class="proyectos__div bg-transparent border-2">Gii Studio</div>
      <div class="proyectos__div bg-transparent border-2">Amazon</div>
      <div class="proyectos__div bg-transparent border-2">Gii Studio</div>
      <div class="proyectos__div bg-transparent border-2">Amazon</div>
      <div class="proyectos__div bg-transparent border-2">Gii Studio</div>
      <div class="proyectos__div bg-transparent border-2">Amazon</div>
    </div>
  </section>
</template>
<style lang="scss">
.proyectos {
  &__title {
    font-size: 2rem;
  }
  &__contenedor {
    flex-wrap: wrap;
    display: flex;
    margin-left: 15px;
  }
  &__div {
    width: 260px;
    height: 260px;
    margin: 10px;
    text-align: center;
    line-height: 75px;
    font-size: 30px;
  }
}
</style>
