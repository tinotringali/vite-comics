<script>

  import AppHeader from './components/AppHeader.vue';
  import AppMainTop from './components/AppMainTop.vue';
  import AppMainBottom from './components/AppMainBottom.vue';
  import AppFooterTop from './components/AppFooterTop.vue';
  import AppFooterBottom from './components/AppFooterBottom.vue';
  import AppJumbotron from './components/AppJumbotron.vue';
 
  export default{
    components:{
      AppHeader,
      AppMainTop,
      AppMainBottom,
      AppFooterTop,
      AppFooterBottom,
      AppJumbotron
    }
  }
</script>

<template>
  <AppHeader></AppHeader>
  <AppJumbotron></AppJumbotron>
  <AppMainTop></AppMainTop>
  <AppMainBottom></AppMainBottom>
  <AppFooterTop></AppFooterTop>
  <AppFooterBottom></AppFooterBottom>
</template>

<style lang="scss">
  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
</style>
