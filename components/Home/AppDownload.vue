<script setup>
import MailsBg from '@/assets/images/mails-background.jpeg'</script>
<template>

  <div
      class="cover-store-profile h-[982px] relative"
      :style="{
        'background-image': 'url(' + MailsBg + ')',
        'background-size': 'cover',
        'background-position': 'center',
        'background-repeat': 'no-repeat'
      }"
  >
    <div class="flex items-center justify-between flex-wrap h-full relative z-10 md:px-[116px] px-[40px] my-auto">
      <div class="flex flex-col md:gap-[24px] gap-[16px]">
        <h1 class="md:text-[64px] text-[28px] font-medium leading-[62px] text-white max-w-[480px]">
          Download APP, get your home
        </h1>
        <p class="md:text-[24px] text-[14px] font-medium leading-[25px] text-white max-w-[550px]">
          Potter ipsum wand elf parchment wingardium. Nagini quaffle candles hand tears downfall. Fluffy snitch cottage for that sight and. Garg
        </p>
        <div class="flex items-center gap-[16px] flex-wrap ">
          <img src="@/assets/images/google-play.png" />
          <img src="@/assets/images/app-store.png" />
        </div>
      </div>

      <img src="@/assets/images/mobile-header.png" />
    </div>

  </div>
</template>
<style scoped>

.cover-store-profile::after {
  background: linear-gradient(0deg, rgba(0, 0, 0, 0.90)0%, rgba(0, 0, 0, 0.00)100%);
  position: absolute;
  top: 0;
  left: 0;
  content: "";
  width: 100%;
  height: 100%;
}
</style>
