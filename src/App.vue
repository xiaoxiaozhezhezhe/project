<template>
  <div id="app">
   <!-- 顶部header -->
   <mt-header fixed title="固定在顶部"></mt-header>
   <!-- 中间 路由 router-view -->
   

   <!-- 底部tabbar -->
  <mt-tabbar v-model="selected">
    <mt-tab-item id="外卖">
      <img slot="icon" src="./assets/img/fenlei.png">
      外卖
    </mt-tab-item>
    <mt-tab-item id="订单">
      <img slot="icon" src="./assets/img/fenlei.png">
      订单
    </mt-tab-item>
    <mt-tab-item id="发现">
      <img slot="icon" src="./assets/img/fenlei.png">
      发现
    </mt-tab-item>
    <mt-tab-item id="我的">
      <img slot="icon" src="./assets/img/fenlei.png">
      我的
    </mt-tab-item>
  </mt-tabbar>
 
  </div>
</template>

<script>
export default {
  name: 'App',
  data(){
    return{
      selected:''
    }
  }
}
</script>

<style>
#app {
  padding-top:5px;
}
</style>
