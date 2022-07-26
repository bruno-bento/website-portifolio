<template>
  <div class="snap-y snap-mandatory h-screen w-full" >
    <div class="snap-start h-screen w-full bg-main-blue flex flex-col">
      <Nav></Nav>
      <Hero></Hero>
    </div>
    <div class="snap-start h-screen w-full flex flex-col bg-white">
      <SubHero></SubHero>
    </div>
    <div class="snap-start h-screen w-full flex flex-col  ">
        <BodyContent></BodyContent>
    </div>

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
    BodyContent,
  },
};
</script>
