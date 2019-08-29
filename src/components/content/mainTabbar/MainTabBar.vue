<template>
  <div id="main-tab-bar">
    <tab-bar>
      <tab-bar-item path="/home">
        <img src="~assets/img/home.svg" alt="icon" slot="item-icon">
        <img src="~assets/img/home-active.svg" alt="icon-active" slot="item-icon-active">
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <img src="~assets/img/category.svg" alt="icon" slot="item-icon">
        <img src="~assets/img/category-active.svg" alt="icon-active" slot="item-icon-active">
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/cart">
        <img src="~assets/img/cart.svg" alt="icon" slot="item-icon">
        <img src="~assets/img/cart-active.svg" alt="icon-active" slot="item-icon-active">
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/profile">
        <img src="~assets/img/profile.svg" alt="icon" slot="item-icon">
        <img src="~assets/img/profile-active.svg" alt="icon-active" slot="item-icon-active">
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
  </div>
</template>

<script>
  import TabBar from 'components/common/tabbar/TabBar'
  import TabBarItem from 'components/common/tabbar/TabBarItem'

  export default {
    name: "MainTabBar",
    components: {
      TabBar,
      TabBarItem
    }
  }
</script>

<style scoped>

</style>