<template>
  <footer class="mt-32 mx-4 flex flex-col">
    <div class="flex flex-col justify-center items-center">
      <div
        class="logo w-12" style="width: 3.5rem;"
        v-html="require(`~/assets/icons/logo.svg?include`)"
      ></div>
      <p class="font-extrabold text-xl mt-2 leading-tight">Local SA</p>
      <p class="font-extrabold leading-tight">Digital Business Card Generator</p>
    </div>
    <p class="mt-6 text-center text-gray-400">
      Save our Trees - Go Digital
    </p>
    <p class="mt-1 mb-8 text-center text-xs text-gray-400">
     <a
        class=""
        href="https://localsa.co.za/"
        target="_blank"
        rel="noopener noreferrer"
        ><b>Local SA</b></a
      > &copy; Copyright 2021 All Rights Reserved
    </p>
  </footer>
</template>

<script>
export default {}
</script>

<style>
</style>
