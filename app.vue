<template>
  <div class="flex flex-col items-center justify-center flex-wrap m-5">
    <Logo
      class="mb-[15px] sm:mb-[100px] max-w-[150px] sm:max-w-[100%] w-full sm:w-auto h-auto"
    />
    <h1
      class="text-white text-center text-[12px] sm:text-[50px] font-bold sm:mb-[20px]"
    >
      Strona w trakcie aktualizacji
    </h1>
    <p class="text-white text-center text-[16px] mb-[12px]">
      W międzyczasie zapraszamy do kontaktu tel.
      <a href="tel:+48730538890">+48 730 538 890</a>
    </p>
    <hr
      class="border-[#01BAC3] border-t-[1px] sm:border-t-[4px] max-w-[25px] sm:max-w-[215px] w-full"
    />
  </div>
</template>

<script setup>
import Logo from "~/assets/images/logo.svg?component";

useHead({
  htmlAttrs: {
    class: "w-full h-full",
  },
  bodyAttrs: {
    class: "w-full h-full bg-[#171232]",
  },
});
</script>

<style>
div#__nuxt,
#__layout,
#__layout > div,
#app {
  @apply min-h-screen flex items-center justify-center;
}
</style>
