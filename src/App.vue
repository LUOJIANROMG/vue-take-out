<template>
<div>
  <router-link to="/order">Order</router-link>
  <router-view/>
  <FooterGuide/>
</div>
</template>

<script>
  import FooterGuide from './components/FooterGuide/FooterGuide'
  export default {
    components:{
      FooterGuide
    }
  }
</script>

<style lang="stylus" rel="stylesheet/stylus">
.app
  color red
</style>
