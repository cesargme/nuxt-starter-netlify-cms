<template>
  <div class="py-20 mx-auto flex justify-center bg-sky-100">
    <div class="prose flex flex-col justify-center">
      <div class="basis-2/4 font-serif text-neutral-500 text-1xl lg:text-2xl">
        La Dra. Julia Méndez
      </div>

      <h1
        class="
          my-4
          text-2xl
          md:text-4xl
          font-bold
          text-neutral-600
          mt-0
          mb-0
          md:mt-4 md:mb-4
        "
      >
        Te da la bienvenida
      </h1>
      <p
        class="
          leading-normal
          text-2xl
          mb-8
          text-neutral-700 text-center
          md:text-left
        "
      >
        Especialista en problemas de
        <span class="text-sky-600 font-bold"
          >columna, pies, lenguaje y aprendizaje</span
        >
      </p>

      <p>20 años de experiencia</p>
    </div>
    <div class="flex">
      <img
        class="
          object-cover object-top
          h-64
          w-64
          rounded-full
          shadow-lg
          bg-white
        "
        src="img/hero.png"
        alt=""
      />
    </div>

  </div>


  
</template>

<script>
export default {
  props: {
    heading: {
      type: String,
      default: null,
    },
    subheading: {
      type: String,
      default: null,
    },
    image: {
      type: String,
      required: true,
    },
  },
}
</script>

<style scoped>
.h-hero {
  height: 25rem;
}
</style>
