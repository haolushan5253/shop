<template>
  <div id="app">
    <keep-alive>
      <router-view v-if="$route.meta.keepAlive"></router-view>
    </keep-alive>
    <router-view v-if="!$route.meta.keepAlive"></router-view>
    <router-view name="footerbar"></router-view>
  </div>
</template>


<script>
// import FooterBar from "./components/FooterBar"
export default {
  // components:{
  //   FooterBar
  // }
}
</script>


<style lang="scss">
</style>
