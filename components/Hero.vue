<template>
  <section class="hero h-screen flex flex-col justify-center pl-10">
    <div class="hero__container text-white">
      <p class="hero__subtitle">I'm Product Designer</p>
      <p class="hero__title">Hello, my name is Roberto.</p>
    </div>
  </section>
</template>
<style lang="scss">
.hero {
  //background-image: url('../assets/images/backgrounds/Fondo-1.jpg');
  background-color: #200082;
  &__container {
    width: 50vw;
    margin-top: 4rem;
    @include screen(desktop) {
      margin-top: 0;
    }
  }
  &__subtitle {
    font-size: 2rem;
  }
  &__title {
    font-size: 4rem;
    @include screen(desktop) {
      font-size: 5rem;
    }
  }
}
</style>
