<template>
  <div>
    <nav-bar class="home-nav">
      <template v-slot:left>
       <img src="~assets/img/recycle-item.png" >
     </template>
    </nav-bar>
    <div class="swiper">
      <swiper>
      <swiper-item><img src="~assets/img/1.png"></swiper-item>
      <swiper-item><img src="~assets/img/2.jpg"></swiper-item>
      <swiper-item><img src="~assets/img/3.jpg"></swiper-item>
    </swiper>
    </div>

    
  </div>
</template>
<script>
import NavBar from 'components/NavBar'
import {Swiper,SwiperItem} from 'components/swiper'

export default {
  name:'home',
  components:{
    NavBar,
    Swiper,
    SwiperItem

  }
}

    Swiper</script>
<style scoped>
  .home-nav{
    background-color:rgb(255,255,255);
  }

  .home-nav img{
    width: 77px;
    height: 35px;
    padding-top: 5px;
  }
  .swiper{
    width: 350px;
    text-align: center;
    /* border:10px,solid,rgb(255,255,255); */
  }


</style>