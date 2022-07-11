<template>
  <div class="h-screen bg-main-blue">
    <Nav></Nav>
    <Hero></Hero>
  </div>
  <div class="h-screen bg-white">
    <div class="flex justify-center">
      <div>Foto</div>
      <div>Sobre</div>
    </div>
    <div class="flex  justify-center">
      <div>Habilidades</div>
      <div>Habilidades</div>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav/index.vue";
import Hero from "./components/Hero/index.vue";
export default {
  components: {
    Nav,
    Hero,
  },
};
</script>
