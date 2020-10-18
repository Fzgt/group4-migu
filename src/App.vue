<template>
  <div class="container">
    <hot-showing></hot-showing>

  </div>
</template>

<script>
import hotShowing from "./views/home/movies/hotShowing.vue"
export default {
  components:{
    hotShowing
  }
}
</script>

<style lang="stylus" scoped>
  .container
    height 100%
</style>
