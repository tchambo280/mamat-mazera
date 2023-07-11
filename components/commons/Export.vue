<template>
  <div id="Skills" class="pt-[4rem]">
    <div class="line w-full bg-gray-300" style="height: 1px"></div>
    <div class="md:mx-[7em] mx-6 pt-10 pb-[3em]">
      <div class="">
        <h1 class="text-4xl md:text-5xl font-bold">SKILLS</h1>
      </div>
      <h1 class="text-xl font-mono pt-10 text-gray-600">
        PROGRAMMING LANGUAGES & TOOLS
      </h1>
      <div class="flex py-8 gap-6">
        <a href="">
          <img
            src="../../assets//imgs/ver.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10 rounded-full"
          />
        </a>
        <a href="#"
          ><img
            src="../../assets/imgs/script-java.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10"
        /></a>
        <a href="#"
          ><img
            src="../../assets/imgs/coding.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10"
        /></a>
        <a href="#"
          ><img
            src="../../assets/imgs/api.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10"
        /></a>
        <a href="#"
          ><img
            src="../../assets/imgs/github.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10 rounded-full"
        /></a>
        <a href="#"
          ><img
            src="../../assets/imgs/mobile-app.png"
            alt=""
            class="transform transition duration-500 hover:scale-125 h-10 w-10 rounded-full"
        /></a>
      </div>
      <div>
        <h1 class="text-xl text-gray-500 pb-4">WORKFLOW</h1>
        <div class="md:flex justify-between items-center mb-20">
          <span class="space-y-2 text-1xm text-gray-700">
            <p><span>➸</span>MObile-First, Responsive Design</p>
            <p><span>➸</span>Agile Development & Scrum</p>
            <p><span>➸</span>Cross Browser Testing & Debugging</p>
            <p><span>➸</span> Cross Functional Teams</p>
          </span>

          <div class="transition transform duration-500 hover:scale-125 mx-10">
            <a
              v-for="(item, index) in navs"
              :key="index"
              class="text-red-600 font-medium text-xl underline pt-[4em]"
              :href="item.path"
              >{{ item.name }}
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'ExportComponent',
  data() {
    return {
      navs: [
        {
          path: '#download',
          name: 'Download CV',
        },
      ],
    }
  },
}
</script>
