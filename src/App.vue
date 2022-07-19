<template>
  <div class="h-screen w-full bg-main-blue flex flex-col">
    <Nav></Nav>
    <Hero></Hero>
  </div>
  <div class="h-screen w-full flex flex-col bg-white">
    <SubHero></SubHero>
  </div>
  <div class="h-screen w-full flex flex-col bg-main-blue">
    <BodyContent></BodyContent> 
  </div>
</template>

<script>
import Nav from "./components/Nav/index.vue";
import Hero from "./components/Hero/index.vue";
import SubHero from "./components/SubHero/index.vue";
import BodyContent from "./components/Body/index.vue";

export default {
  components: {
    Nav,
    Hero,
    SubHero,
    BodyContent
  },
};
</script>
