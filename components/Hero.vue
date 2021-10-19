<template>
  <section class="hero h-screen flex flex-col justify-center pl-10">
    <div class="hero__container text-white">
      <p class="hero__subtitle">I'm Product Designer</p>
      <p class="hero__title">Hello, my name is Roberto.</p>
      <div>
        <img class="h-10 w-10" :src="face" alt="" />
      </div>
    </div>
  </section>
</template>
<script>
import face from '../assets/images/icons/facebook.svg'
export default {
  data() {
    return {
      face: face,
    }
  },
}
</script>
<style lang="scss">
.hero {
  //background-image: url('../assets/images/backgrounds/Fondo-1.jpg');
  background-color: #200082;
  &__container {
    width: 50vw;
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
