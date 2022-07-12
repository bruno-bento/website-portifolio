<template>
  <div class="h-screen bg-main-blue">
    <Nav></Nav>
    <Hero></Hero>
  </div>
  <div class="h-screen bg-white">
    <SubHero></SubHero>
  </div>
</template>

<script>
import Nav from "./components/Nav/index.vue";
import Hero from "./components/Hero/index.vue";
import SubHero from "./components/SubHero/index.vue";
export default {
  components: {
    Nav,
    Hero,
    SubHero,
  },
};
</script>
