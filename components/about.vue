<template>
  <section class="about flex h-screen">
    <div class="about__divLeft flex flex-col justify-center items-center">
      <span class="about__title">My specialization</span>
      <span class="about__subtitle"
        >I am a trending designer who cares about the details</span
      >

      <div class="about__indice font-bold mt-10">
        <ul>
          <li>01. HOME DESIGN</li>
          <li>02. COMMERCIAL DESIGN</li>
          <li>03. PRODUCT DESIGN</li>
          <li>04. WEBSITE DESIGN</li>
          <li>05. LANDSCAPE DESIGN</li>
        </ul>
      </div>
    </div>
    <div class="about__divRight flex justify-center items-center">
      <img src="..\assets\images\foto.jpg" alt="" />
    </div>
  </section>
</template>
<style lang="scss">
.about {
  &__divLeft {
    width: 50vw;
  }
  &__divRight {
    width: 50vw;
  }
}
</style>
