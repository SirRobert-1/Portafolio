<template>
  <section
    class="
      contacto
      flex
      xs:flex-col
      lg:flex-row
      xs:h-full
      lg:h-screen
      bg-negro
      text-white
    "
  >
    <div
      class="
        contacto__divLeft
        flex flex-col
        justify-center
        xs:items-start
        lg:items-center
        xs:pl-5
        lg:px-20
      "
    >
      <span class="contacto__title mb-5">Contáctame</span>
      <span></span>
      <span class="contacto__direccion">69 Queen St, Melbourne Australia</span>
      <span class="contacto__telefono">22 81 60 40 84</span>
      <span class="contacto__correo">rviverosgonzalez@gmail.com</span>
    </div>
    <div
      class="
        contacto__divRight
        flex flex-col
        justify-center
        items-start
        xs:pl-5
      "
    >
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
        <button
          class="
            contacto__boton
            bg-rojo
            hover:bg-rojiso
            py-1
            px-3
            rounded-lg
            xs:mb-5
            lg:mb-2
          "
        >
          Contáctame
        </button>
      </form>
    </div>
  </section>
</template>
<style lang="scss">
.contacto {
  //background-image: url(../assets/images/backgrounds/Fondo-1.jpg);
  background-color: #200082;
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
    font-size: 2rem;
  }
  &__direccion {
    font-size: 1.5rem;
  }
  &__telefono {
    font-size: 1.5rem;
  }
  &__correo {
    font-size: 1.5rem;
  }
  &__titulo {
    font-size: 1.5rem;
  }
  &__input {
    background-color: transparent;
    border-bottom: 1px solid white;
    width: 300px;
    height: 50px;
    padding-left: 1rem;
    margin-bottom: 2rem;
    @include screen(desktop) {
      width: 500px;
    }
  }
  &__img {
    width: 50px;
    height: 50px;
  }
}
</style>
