<template>
  <div class="snap-y snap-mandatory h-screen w-full" >
    <div class="snap-start h-screen w-full bg-main-blue flex flex-col">
      <Nav></Nav>
      <Hero></Hero>
    </div>
    <div class="snap-start h-screen w-full flex flex-col ">
      <SubHero></SubHero>
    </div>
    <div class="snap-start h-screen w-full flex flex-col  ">
        <BodyContent></BodyContent>
    </div>
    <div class="snap-start h-screen w-full flex flex-col  ">
        <SubBody></SubBody>
    </div>
    <div class="snap-start h-screen w-full flex flex-col bg-white ">
    </div>    
    <div class="snap-start h-3/6 w-full flex flex-col">
        <Footer></Footer>
    </div>
  </div>
</template>

<script>
import Nav from "./components/Nav/index.vue";
import Hero from "./components/Hero/index.vue";
import SubHero from "./components/SubHero/index.vue";
import BodyContent from "./components/Body/index.vue";
import SubBody from "./components/SubBody/index.vue";
import Footer from "./components/Footer/index.vue";
export default {
  components: {
    Nav,
    Hero,
    SubHero,
    BodyContent,
    SubBody,
    Footer
  },
};
</script>
