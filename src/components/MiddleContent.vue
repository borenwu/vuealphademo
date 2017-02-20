<template>
  <main class="mn-inner inner-active-sidebar">
    <div class="middle-content">
      <router-view></router-view>
    </div>
  </main>
</template>

<style>

</style>

<script>
    export default{
        data(){
            return{
                msg:'hello middle content'
            }
        },
        components:{

        }
    }
</script>
