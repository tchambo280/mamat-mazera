<template>
  <div id="about" class="mb-20">
    <div class="mt-[8em] mx-6 md:mx-[7em]">
      <h1 class="font-semibold text-5xl">
        <span class="font-sans text-gray-500">MAMAT</span>
        MAMAT
      </h1>
      <p class="font-bold md:text-2xl pt-3 text-md">
        <span class="text-gray-500"> CAMEROON</span> MAMAT-MAMAT 280 @ GMAIL.COM
      </p>
      <p class="md:text-lg text-gray-500 pt-10 text-sm font-sans">
        I am a software developer experienced in Javascript, NodeJs, HTML(5),
        CSS(3),<br />
        Tailwind-css, agile SCRUM development methodologies
      </p>
      <div class="flex md:gap-7 pt-10 gap-3">
        <div class="md:h-10 md:w-10 h-10 w-10 rounded-full">
          <img
            src="../../assets/imgs/github.png"
            alt=""
            class="transform transition duration-500 hover:scale-125"
          />
        </div>
        <div class="rounded-full flex items-center justify-center">
          <img
            src="../../assets/imgs/tweetr.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 md:h-10 md:w-10 h-10 w-10 rounded-full bg-gray-500 p-2"
          />
        </div>

        <div class="rounded-full flex center">
          <img
            src="../../assets/imgs/instagram.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 md:h-10 md:w-10 h-10 w-10 rounded-full"
          />
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'EperienceComponent',
  data() {
    return {
      navs: [
        {
          path: '#',
          name: '../assets/imgs/logo.png',
        },
      ],
    }
  },
}
</script>
