<template>
  <footer class="mt-32 mx-4 flex flex-col">
    <div class="flex flex-col justify-center items-center">
      <div
        class="logo w-12" style="width: 13.5rem;border: 3px solid #fff;padding: 15px;border-radius: 15px;"
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
/* width */
::-webkit-scrollbar {
  width: 10px;
}

/* Track */
::-webkit-scrollbar-track {
  background: #ffffffde;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: #888;
}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: #555;
}

div#step-1, div#step-2, div#step-3, div#step-4, div#step-5, div#step-6, div#step-7, div#step-8, div#step-9, div#step-10, div#downloadSection, div#donate {
    padding: 15px;
    background-color: #eee;
    border-radius: 10px
}

h2.font-extrabold.text-2xl {
    color: black !important;
    text-transform: capitalize;
}

.flex.mt-6.mb-6 {
    background-color: #111827;
}

.ml-4 {
    margin-left: 0;
    color: #000;
    font-weight: 600;
}

.px-4.mt-32 {
    background-color: #fff0;
}

button.p-3.flex-shrink-0.rounded-full.hover\:scale-125.focus\:scale-125.transform.transition-transform.duration-200.focus\:outline-none {
    border-radius: 25%;
}

.w-12 {
    width: 7rem;
}

.object-contain {
    object-fit: cover;
}

p {
    color: black !important;
}

.px-4 {
    padding-left: 1rem;
    padding-right: 1rem;
    padding-top: 1rem;
    padding-bottom: 1rem;
}
.leading-none {
    line-height: 1;
    color: #eee !important;
}
.flex.flex-wrap.items-center {
    background-color: #1f2937d1;
    padding-right: 15px;
}
.bg-gray-900 {
    background-image: url(https://www.gumcars.co.za/demo/bgd.jpg);
    background-position: center center;
    background-repeat: repeat;
    background-attachment: fixed;
}
</style>
