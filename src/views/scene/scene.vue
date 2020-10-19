<template>
  <div class="container">
    <header>
      autumn
      <van-swipe :autoplay="3000">
        <van-swipe-item v-for="(image, index) in images" :key="index">
          <img v-lazy="image" />
        </van-swipe-item>
      </van-swipe>
       winter
    </header>
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
import Vue from 'vue';
import { Lazyload } from 'vant';
import { Swipe, SwipeItem } from 'vant';

Vue.use(Lazyload);
Vue.use(SwipeItem);
Vue.use(Swipe);

export default {
  data() {
    return {
      images: [
        'https://img.yzcdn.cn/vant/apple-1.jpg',
        'https://img.yzcdn.cn/vant/apple-2.jpg',
      ],
    };
  },
};
</script>


<style lang="stylus" scoped>



img
  width 334.5px
  height 183.5px

</style>