<template>
  <div class="container">
    <scene></scene>

  </div>
</template>

<script>
import scene from "./views/scene/scene.vue"
export default {
  components:{
    scene
  }
}
</script>

<style lang="stylus" scoped>
  .container
    height 100%
</style>
