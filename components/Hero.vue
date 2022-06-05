<template>
  <div class="flex justify-center bg-sky">
    <div class="flex flex-col justify-center">
      <div class="basis-2/4 font-serif text-neutral-500 text-1xl lg:text-2xl">
        La Dra. Julia Méndez
      </div>
      <h1 class="basis-1/4">Te da la bienvenida</h1>
      <div class="basis-1/4">hola</div>
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
