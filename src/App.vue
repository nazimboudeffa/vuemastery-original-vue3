<template>
  <div id="app">
    <nav-bar/>
    <router-view/>

  <hero-banner />

  </div>
</template>

<script>
import NavBar from '@/components/nav-bar'
import HeroBanner from '@/components/hero-banner'

export default {
  components: {
    NavBar,
    HeroBanner
  },
  name: 'app'
}
</script>

<style lang="scss">
   @import 'style.scss';
</style>
