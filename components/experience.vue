<template>
  <section class="experience xs:h-full lg:h-screen lg:py-10">
    <p class="experience__title text-center mb-5 text-darkBlue">Experiencia</p>
    <div class="swiper-container">
      <!-- Additional required wrapper -->
      <div class="swiper-wrapper text-darkBlue">
        <!-- Slides -->
        <div class="swiper-slide">
          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\Html.png"
              alt=""
              class="experience__logos"
            />
            <p class="experience__tecnologias">Html</p>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\Css.png"
              alt=""
              class="experience__logos"
            />
            <span class="experience__tecnologias">CSS</span>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>

          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\JavaScript.png"
              alt=""
              class="experience__logos"
            />
            <span class="experience__tecnologias">JavaScript</span>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
        </div>
        <div class="swiper-slide">
          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\vue.png"
              alt=""
              class="experience__logos"
            />
            <span class="experience__tecnologias">Vue</span>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>

          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\vuetify.png"
              alt=""
              class="experience__logos"
            />
            <span class="experience__tecnologias">Vuetify</span>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>

          <div
            class="
              experience__div
              flex
              xs:flex-col
              lg:flex-row
              justify-around
              items-center
            "
          >
            <img
              src="..\assets\images\nuxt.png"
              alt=""
              class="experience__logos"
            />
            <span class="experience__tecnologias">Nuxt</span>
            <p class="experience__texto">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
        </div>
      </div>
      <!-- If we need pagination -->
      <div class="swiper-pagination"></div>

      <!-- If we need navigation buttons -->
      <div class="swiper-button-prev"></div>
      <div class="swiper-button-next"></div>
    </div>
  </section>
</template>
<script>
import Swiper from 'swiper/bundle'
import 'swiper/swiper-bundle.css'

export default {
  mounted() {
    this.slider()
  },
  methods: {
    slider() {
      const swiper = new Swiper('.swiper-container', {
        effect: 'slide',
        slidesPerView: 1,
        loop: true,
        pagination: {
          el: '.swiper-pagination',
          type: 'bullets',
        },
        navigation: {
          nextEl: '.swiper-button-next',
          prevEl: '.swiper-button-prev',
        },
      })
      return swiper
    },
  },
}
</script>
<style lang="scss">
.experience {
  &__div {
    margin-bottom: 2rem;
    padding: 0 5rem;
  }
  &__title {
    font-size: 2rem;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }
  &__texto {
    @include screen(desktop) {
      width: 500px;
    }
  }
  &__tecnologias {
    font-size: 1.5rem;
    font-family: 'Times New Roman', Times, serif;
  }
  &__logos {
    height: 100px;
    width: 100px;
    object-fit: cover;
  }
}
</style>
