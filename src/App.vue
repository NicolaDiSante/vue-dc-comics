<template>
  <div id="app">

    <Header />
    <Main />
    <ContentSection />
    <FooterTop />
    <FooterBottom />



    
  </div>
</template>

<script>

import Header from './components/Header.vue';
import Main from './components/Main.vue';
import ContentSection from './components/ContentSection.vue';
import FooterTop from './components/FooterTop.vue';
import FooterBottom from './components/FooterBottom.vue';


export default {
  name: "App",
  components: {
    Header,
    Main,
    ContentSection,
    FooterTop,
    FooterBottom
  },
};
</script>

<style lang="scss">

@import './assets/style/general.scss';


</style>
