<script setup>
import DiscoverImg from "assets/images/discover-img.png";
import SofaImg from "assets/images/sofa-img.png";
</script>

<template>
  <div class="bg-black">

    <div class="grid grid-cols-12">
      <div class="lg:col-span-7 col-span-12 pt-[63px] mb-72">
        <h1 class="text-center text-white font-bold md:text-[64px] text-[28px] mb-[9px]">
          Discover Your New Home
        </h1>

        <div class="flex items-center justify-between flex-wrap h-full ms-[65px]">
            <p class="md:text-[24px] text-[14px] font-medium leading-[25px] text-white 2xl:max-w-[485px]  max-w-[385px]">
              Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg
            </p>
        </div>
      </div>
      <div class="lg:col-span-5 col-span-12">
        <div
            class=" h-[982px] relative"
            :style="{
        'background-image': 'url(' + DiscoverImg + ')',
        'background-size': 'cover',
        'background-position': 'center',
        'background-repeat': 'no-repeat'
      }"
        >
          <div class="flex items-center justify-between h-full w-full absolute z-10 my-auto mx-auto 2xl:left-[-500px] lg:left-[-300px] left-0 xl:top-0 top-[-500px]">
            <div class="2xl:w-[608px] 2xl:h-[543px] md:w-[308px] md:h-[243px] w-[335px] h-[276px]">
            <img src="@/assets/images/sofa-img.png"  />
            </div>
          </div>

        </div>
      </div>
    </div>
  </div>
</template>
<style scoped>

</style>