<template>
  <div>
    <tab-bar>
      <tab-bar-item path='/home'>
        <template v-slot:item-icon>
          <img src="~assets/img/tabbar/home.svg" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/tabbar/home_active.svg" alt="">
        </template>
        <template v-slot:item-name>
          <div>首页</div>
        </template>
      </tab-bar-item>
      <tab-bar-item path='/category'>
        <template v-slot:item-icon>
          <img src="~assets/img/tabbar/category.svg" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/tabbar/category_active.svg" alt="">
        </template>
        <template v-slot:item-name>
          <div>分类</div>
        </template>
      </tab-bar-item>
      <tab-bar-item path='/profile'>
        <template v-slot:item-icon>
          <img src="~assets/img/tabbar/profile.svg" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/tabbar/profile_active.svg" alt="">
        </template>
        <template v-slot:item-name>
          <div>我的</div>
        </template>
      </tab-bar-item> 
    </tab-bar>
  </div>
    
</template>
<script>

import TabBar from './TabBar'
import TabBarItem from './TabBarItem'

export default {
  name:'MainTabBar',
  components:{
    TabBar,
    TabBarItem
  }
}
</script>
<style scoped>
  
</style>