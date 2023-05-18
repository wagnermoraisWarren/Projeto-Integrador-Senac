<template>
  <div class="home">
    <Header />
    <Banner />
    <Goals />
    <Footer />
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Banner from '@/components/Banner.vue';
import Goals from '@/components/Goals.vue';
import Footer from '@/components/Footer.vue';
export default {
  name: 'Home',

  components: {
    Header,
    Banner,
    Goals,
    Footer
  }

}
</script>