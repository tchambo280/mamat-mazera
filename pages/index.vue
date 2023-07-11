<template>
  <div class="bg-gradient-to-b from-sky-50 to-white">
    <!--Header-->
    <Header />
    <!--Acceill-->
    <Experience />
    <!--3-->

    <Education />

    <export />
    <!--FOOTER-->
    <pond />
  </div>
</template>
<script>
import Education from '~/components/commons/Education.vue'
import Experience from '~/components/commons/Experience.vue'
import Export from '~/components/commons/Export.vue'
import Header from '~/components/commons/header.vue'
import Pond from '~/components/commons/pond.vue'
export default {
  name: 'IndexPage',
  components: { Header, Experience, Export, Education, Pond },
  layout: 'layout',
}
</script>
<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;900&display=swap');
</style>
