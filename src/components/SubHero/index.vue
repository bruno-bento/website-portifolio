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
        <div class="flex flex-col items-center w-4/6 h-4/6 bg-main-yellow rounded-md" >
          <p class="font-bold text-main-blue mt-4 text-2xl">Sobre</p>
          <p class="font-regular text-main-blue mt-4 text-center text-lg">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
            eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim
            ad minim veniam, culpa qui officia deserunt mollit anim id est
            laborum. Lorem ipsum dolor sit amet, consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, culpa qui officia deserunt mollit anim id
            est laborum. Lorem ipsum dolor sit amet, consectetur adipiscing
            elit, sed do eiusmod tempor incididunt ut labore et dolore magna
            aliqua. Ut enim ad minim veniam, culpa qui officia deserunt mollit
            anim id est laborum.
          </p>
        </div>
      </div>
      <div class="flex flex-col justify-start items-center bg-main-blue w-full rounded h-2/6">
        <p class="text-white font-regular py-5 text-xl font-bold">Habilidades</p>
      </div>
    </div>
  </section>
</template>

<style lang="postcss" scoped>
.shadow {
  filter: drop-shadow(10px 10px 0px #ffd02b)
    drop-shadow(-10px -10px 0px #ffd02b);
}
</style>
