<template>
  <section class="proyectos xs:h-full lg:h-screen bg-beige px-5 text-darkBlue">
    <p class="proyectos__title text-center lg:text-left text-4xl my-5">
      Participaciones
    </p>

    <div class="proyectos__contenedor flex flex-wrap justify-around lg:my-24">
      <div class="proyectos__div bg-white border-2">Gii Studio</div>
      <div class="proyectos__div bg-white border-2">Rb Construcción</div>
      <div class="proyectos__div bg-white border-2">Vortex</div>
    </div>
  </section>
</template>
<style lang="scss">
.proyectos {
  background-image: url(../assets/images/backgrounds/bg2.png);
  background-repeat: no-repeat;
  background-size: cover;
  &__div {
    width: 260px;
    height: 260px;
    margin-bottom: 1rem;
    margin-top: 1rem;
    text-align: center;
    line-height: 75px;
    font-size: 30px;
  }
}
</style>
