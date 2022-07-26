<template>
  <section class="flex justify-center items-center w-full h-full">
    <div class="flex flex-col justify-around items-center h-5/6 w-5/6">
      <div class="flex justify-between items-center w-full gap-5 h-5/6">
        <div class="flex items-center w-2/6">
          <img
            class="rounded-md w-4/6 h-4/6 filter shadow"
            src="../../assets/images/profilePicture.jpeg"
            alt="profilePicture"
          />
        </div>
        <div class="flex flex-col justify-evenly items-center w-4/6 h-4/6 bg-main-yellow rounded-md" >
          <p class="font-bold text-main-blue text-2xl ">Sobre</p>
          <div class="w-full h-4/6 px-5 overflow-hidden">
            <p class=" text-main-blue text-center text-lg">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
              ad minim veniam, culpa qui officia deserunt mollit anim id est
              laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit,
              sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
              Ut enim ad minim veniam, culpa qui officia deserunt mollit anim id
              est laborum.
            </p>
          </div>
        </div>
      </div>
      <div class="flex flex-col justify-start items-center bg-main-blue w-full rounded h-2/6">
        <p class="text-white text-center font-regular py-5 text-xl font-bold ">Habilidades</p>
        <div class="flex justify-between  items-center w-full h-full mb-5 px-5">
          <Icon name="ArrowLeft"  :color="mainColors.yellow" />
          <Icon name="ArrowRight" :color="mainColors.yellow" />
        </div>
      </div>
    </div>
  </section>
</template>


<script>
import Icon from '../Icons/index.vue'
export default {
  components: {
    Icon
  },
  setup() {
    return{
      mainColors: { yellow: '#FFD02B' }
    }
  }
}
</script>

<style lang="postcss" scoped>
.shadow {
  filter: drop-shadow(10px 10px 0px #ffd02b)
    drop-shadow(-10px -10px 0px #ffd02b);
}
</style>
