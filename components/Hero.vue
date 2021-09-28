<template>
  <section class="hero h-screen flex flex-col justify-center bg-negro">
    <div
      class="
        hero__container
        flex flex-col
        items-center
        justify-center
        text-white
      "
    >
      <div class="hero__title">
        I'm Product Designer Hello, my name is Roberto.
      </div>
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
  &__container {
    width: 50vw;
  }
  &__title {
    font-size: 5rem;
  }
}
</style>
