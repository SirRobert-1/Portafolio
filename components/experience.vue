<template>
  <section class="h-screen">
    <p>Experience</p>
    <div class="swiper-container">
      <!-- Additional required wrapper -->
      <div class="swiper-wrapper">
        <!-- Slides -->
        <div class="swiper-slide">
          <div>
            <p>Vue</p>
            <p>Nuxt</p>
            <p>Vuetify</p>
          </div>
        </div>
        <div class="swiper-slide">
          <div>
            <p>Vue</p>
            <p>Nuxt</p>
            <p>Vuetify</p>
          </div>
        </div>
        <div class="swiper-slide">
          <div>
            <p>Vue</p>
            <p>Nuxt</p>
            <p>Vuetify</p>
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
