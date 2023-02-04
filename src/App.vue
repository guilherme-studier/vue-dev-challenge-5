<template>
  <Header />
  <Images />
  <Footer />
</template>

<script>
import Header from './components/Header.vue';
import Images from './components/Images.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  components: {
    Header,
    Images,
    Footer,
  }
}
</script>
