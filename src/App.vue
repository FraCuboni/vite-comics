<script>
  import Header from './components/AppHeader.vue';
  import Content from './components/AppContent.vue';
  import Info from './components/AppInfo.vue';
  import FooterTop from './components/AppFooterTop.vue';
  import FooterBottom from './components/AppFooterBottom.vue';
  export default{
    components :{
      Header,
      Content,
      Info,
      FooterTop,
      FooterBottom,
    }
  }
</script>

<template>
    <Header/>
    <Content/>
    <Info/>
    <FooterTop/>
    <FooterBottom/>
</template>

<style lang="scss" scoped>

.container{
  width: 100%;
  height: 100%;
}

</style>