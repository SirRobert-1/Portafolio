<template>
  <section class="h-screen">
    <nav>Roberto 5659497845 designer@gmail.com</nav>
    <div>I'm Product Designer Hello, my name is Denzel.</div>
    <div>
      <img class="h-10 w-10" :src="face" alt="" />
    </div>
  </section>
</template>
<script>
import face from '@@/assets/images/icons/facebook.svg'
export default {
  data() {
    return {
      face: face,
    }
  },
}
</script>
