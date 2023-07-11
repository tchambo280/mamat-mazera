<template>
  <div>
    <!-- header -->
    <Header />

    <nuxt />
    <!-- footer -->
    <Footer />
  </div>
</template>
<script>
import header from './commons/header.vue'
export default {
  name: 'LayoutCoponent',
  components: { header },
}
</script>
