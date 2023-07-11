<template>
  <div class="border-t-2">
    <div class="md:flex justify-between md:mx-[7em] mx-6 py-5">
      <h1 class="text-gray-500 font-semibold text:sm">
        Copyright @ 2023 Mamat- All rights reserved
      </h1>
      <div class="md:flex space-x-6 text-md font-semibold text-gray-500 hidden">
        <a v-for="(item, index) in navs" :key="index" :href="item.path">{{
          item.name
        }}</a>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: 'PondComponents',
  data() {
    return {
      navs: [
        {
          path: '#about',
          name: 'About',
        },

        {
          path: '#education',
          name: 'Education',
        },
        {
          path: '#Skills',
          name: 'Skills',
        },
      ],
    }
  },
}
</script>
