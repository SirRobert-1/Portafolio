<template>
  <section class="experience h-screen">
    <p class="experience__title flex justify-center">Experience</p>
    <div class="swiper-container">
      <!-- Additional required wrapper -->
      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide flex flex-col">
          <div class="flex flex-row justify-around">
            <img
              src="..\assets\images\vue.png"
              alt=""
              height="150"
              width="150"
            />
            <span class="flex items-center">Html</span>
            <p class="experience__texto mb-10 mt-10">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
          <div class="swiper-slide flex flex-col">
            <div class="flex flex-row justify-around">
              <img
                class="mt-5 mb-5"
                src="..\assets\images\vuetify.png"
                alt=""
                height="150"
                width="150"
              />
              <span class="flex items-center">CSS</span>
              <p class="experience__texto mb-10 mt-10">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
          </div>
          <div class="swiper-slide flex flex-col">
            <div class="flex flex-row justify-around">
              <img
                src="..\assets\images\nuxt.png"
                alt=""
                height="150"
                width="150"
              />
              <span class="flex items-center">JavaScript</span>
              <p class="experience__texto mb-10 mt-10">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
          </div>
        </div>
        <div class="swiper-slide flex flex-col">
          <div class="flex flex-row justify-around">
            <img
              class="mt-5 mb-5"
              src="..\assets\images\vue.png"
              alt=""
              height="150"
              width="150"
            />
            <span class="flex items-center">Vue</span>
            <p class="experience__texto mb-10 mt-10">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
              enim ad minim veniam, quis nostrud exercitation ullamco laboris
              nisi ut aliquip ex ea commodo consequat.
            </p>
          </div>
          <div class="swiper-slide flex flex-col">
            <div class="flex flex-row justify-around">
              <img
                src="..\assets\images\vuetify.png"
                alt=""
                height="150"
                width="150"
              />
              <span class="flex items-center">Vuetify</span>
              <p class="experience__texto mb-10 mt-10">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
          </div>
          <div class="swiper-slide flex flex-col">
            <div class="flex flex-row justify-around">
              <img
                src="..\assets\images\nuxt.png"
                alt=""
                height="150"
                width="150"
              />
              <span class="flex items-center">Nuxt</span>
              <p class="experience__texto mb-10 mt-10">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </p>
            </div>
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
  &__title {
    font-size: 2rem;
    font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
  }
  &__texto {
    width: 500px;
  }
}
</style>
