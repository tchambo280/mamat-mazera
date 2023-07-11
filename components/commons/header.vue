<template>
  <header class="sticky top-0 z-50">
    <nav class="shadow-lg">
      <div class="max-w-full">
        <div class="">
          <div class="md:flex justify-between items-center bg-white">
            <div class="md:px-20 py-3">
              <a href="#" class="flex md:justify-center md:items-center">
                <img
                  :src="profile"
                  alt=""
                  class="w-10 h-10 rounded-full center bg-cover"
                />
                <span class="font-bold text-xl mx-3 font-sans text-gray-500"
                  >Mamat</span
                >
              </a>
            </div>

            <div
              class="md:flex space-x-6 text-lg font-semibold text-gray-600 hidden pr-20"
            >
              <a v-for="(item, index) in navs" :key="index" :href="item.path">{{
                item.name
              }}</a>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {
  name: 'HeaderComponent',
  data() {
    return {
      profile: require('../../assets/imgs/mamat.png'),
      navs: [
        {
          path: '#about',
          name: 'ABOUT',
        },

        {
          path: '#education',
          name: 'EDUCATION',
        },
        {
          path: '#Skills',
          name: 'SKILLS',
        },
      ],
    }
  },
}
</script>
