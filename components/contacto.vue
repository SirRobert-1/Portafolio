<template>
  <section class="contacto flex h-screen bg-negro text-white">
    <div class="contacto__divLeft flex flex-col justify-center items-center">
      <span class="contacto__title">Contáctame</span>
      <span></span>
      <span class="contacto__direccion">69 Queen St, Melbourne Australia</span>
      <span class="contacto__telefono">5659497845</span>
      <span class="contacto__correo">designer@gmail.com</span>
    </div>
    <div class="contacto__divRight flex flex-col justify-center items-start">
      <span class="contacto__titulo mb-5">Contáctame por correo</span>
      <form
        class="contacto__formulario flex flex-col justify-center items-start"
      >
        <input
          class="contacto__input"
          type="text"
          name="Nombre"
          id="Nombre"
          placeholder="Nombre"
        />
        <input
          class="contacto__input"
          type="email"
          name="Email"
          id="email"
          placeholder="Correo"
        />
        <textarea
          class="contacto__input"
          type="text"
          name="Mensaje"
          id="mensaje"
          placeholder="Mensaje"
        >
        </textarea>
        <button class="contacto__boton bg-rojo py-1 px-3">Contáctame</button>
      </form>
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
  &__input {
    background-color: transparent;
    border-bottom: 1px solid white;
    width: 500px;
    height: 50px;
    padding-left: 1rem;
    margin-bottom: 2rem;
  }
}
</style>
