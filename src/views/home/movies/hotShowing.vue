<template>
  <div class="container">
    <header>狗眼电影</header>
    <main>
      <nav></nav>
      <ul>
        <li></li>
      </ul>
    </main>
    <footer>
      <ul>
        <li>电影</li>
        <li>影院</li>
        <li>我的</li>
      </ul>
    </footer>
  </div>
</template>

<script>
export default {};
</script>


<style lang="stylus" scoped>
.container
    height: 100%
    display flex
    flex-direction column
    header 
        height .44rem
        background #cc4c43
        text-align center
        line-height .44rem
        font-size .16rem
        font-weight bold
        color #fff

    main
        flex 1

    footer 
      height .5rem
      ul 
        height 100%
        display flex
        border-top solid 1px #ccc
        li 
          flex 1
          text-align center
          line-height .5rem
          justify-content center
          align-items center
          font-size .2rem
          
</style>