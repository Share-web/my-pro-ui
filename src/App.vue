<template>
  <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view />
  </div>
</template>
<script>
//TODO::
export default {
  //mdn document;// js某个关键字的含义
  //mdn Object.keys;//es6:对象的keys组成的数组
  //mdn object.values;//es6:对象的vules组成的数组
  //mdn Array.slice;//删除或截取下标的元素
  //mdn array.splice;//插入或替换下标的元素
};
</script>
//FIXME:
<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
