<template>
<!--  和index.html里面id="app"的没有关系,他只是对应下面的样式-->
  <div id="app">
    <router-view/>
  </div>
</template>
<script>

  import NavMenu from '@/components/common/NavMenu'
// export default 意思是将这个组件整体导出，之后就可以使用import导入组件
//   大括号里面是这个组件的相关属性
  export default {
    name: 'App',
    components: {NavMenu}
  }
</script>

<style>
  #app {
    font-family: 'Avenir', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    text-align: center;
    color: #2c3e50;
    /*margin-top: 10px;*/
  }
</style>
