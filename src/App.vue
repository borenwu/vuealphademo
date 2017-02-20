<template>
  <div class="mn-content fixed-sidebar">
    <app-header></app-header>
    <side-nav></side-nav>
    <middle-content></middle-content>
  </div>
</template>

<script>
  import AppHeader from 'components/AppHeader'
  import SideNav from 'components/SideNav'
  import MiddleContent from 'components/MiddleContent'
  export default {
    name: 'app',
    data(){
      return {
        msg: 'hello app'
      }
    },
    components: {
      AppHeader,
      SideNav,
      MiddleContent
    }
  }
</script>

<style>


</style>
