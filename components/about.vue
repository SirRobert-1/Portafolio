<template>
  <section class="about flex xs:flex-col lg:flex-row xs:h-full lg:h-screen">
    <div
      class="
        about__divLeft
        flex flex-col
        justify-center
        items-start
        xs:px-5
        lg:px-20
        text-white
      "
    >
      <span class="about__title my-5">My specialization</span>
      <span class="about__subtitle font-bold"
        >I am a trending designer who cares about the details</span
      >

      <div class="about__indice mt-5 mb-10">
        <ul>
          <li class="mb-5">01. HOME DESIGN</li>
          <li class="mb-5">02. COMMERCIAL DESIGN</li>
          <li class="mb-5">03. PRODUCT DESIGN</li>
          <li class="mb-5">04. WEBSITE DESIGN</li>
          <li class="mb-5">05. LANDSCAPE DESIGN</li>
        </ul>
      </div>
    </div>
    <div class="about__divRight flex justify-center items-center px-5">
      <img src="@/assets/images/foto.jpg" alt="" />
    </div>
  </section>
</template>
<style lang="scss">
.about {
  background-image: url(../assets/images/backgrounds/bg1.png);
  background-repeat: no-repeat;
  background-size: cover;
  &__divLeft {
    width: 100vw;
    @include screen(desktop) {
      width: 50vw;
    }
  }
  &__divRight {
    width: 100vw;
    @include screen(desktop) {
      width: 50vw;
    }
  }
  &__title {
    font-size: 1.5rem;
  }
  &__subtitle {
    font-size: 3rem;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }
  &__indice {
    font-size: 1.25rem;
    font-family: Arial, Helvetica, sans-serif;
  }
}
</style>
