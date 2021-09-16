<template>
  <section class="contacto flex h-screen">
    <div class="contacto__divLeft flex flex-col justify-center items-center">
      <span class="contacto__title">Contáctame</span>
      <span></span>
      <span class="contacto__direccion">69 Queen St, Melbourne Australia</span>
      <span class="contacto__telefono">5659497845</span>
      <span class="contacto__correo">designer@gmail.com</span>
    </div>
    <div class="contacto__divRight flex flex-col justify-center items-start">
      <span class="contacto__formulario">Contáctame por correo</span>
      <input type="text" name="Nombre" id="Nombre" placeholder="Nombre" />
      <input type="email" name="Email" id="email" placeholder="Correo" />
      <input type="text" name="Mensaje" id="mensaje" placeholder="Mensaje" />
      <button class="contacto__boton bg-rojo">Contactame</button>
    </div>
  </section>
</template>
<style lang="scss">
.contacto {
  &__divLeft {
    width: 50vw;
  }
  &__divRight {
    width: 50vw;
  }
}
</style>
