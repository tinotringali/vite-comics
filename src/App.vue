<script>

  import AppHeader from './components/AppHeader.vue';
  import AppMainTop from './components/AppMainTop.vue';
  import AppMainBottom from './components/AppMainBottom.vue';
  import AppFooterTop from './components/AppFooterTop.vue';
  import AppFooterBottom from './components/AppFooterBottom.vue';
 

  export default{
    components:{
      AppHeader,
      AppMainTop,
      AppMainBottom,
      AppFooterTop,
      AppFooterBottom
    }
  }
</script>

<template>
  <AppHeader></AppHeader>
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

  body{
    margin: 0 auto;
  }
  
</style>
