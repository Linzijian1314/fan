<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">
.size{
  width: 100%;
  height: 100%;
}
html,body{
  .size;
  overflow: hidden;
  margin: 0;
  padding: 0;
}
#app {
  .size;
}
.ivu-layout-sider{
    // width: 170px!important;
    min-width: 170px!important;
    max-width: 170px!important;
    font-size: 50px!important;
}
.ivu-layout-sider-collapsed {
    width:  64px!important;
    min-width:  64px!important;
    max-width:  64px!important;
}
.ivu-menu-item{
      padding: 14px 35px!important;
      font-size: 18px!important;
}
.ivu-menu-item span{
      // padding: 14px 35px!important;
      font-size: 14px!important;
}
.logo-con,
.logo-con img {
  width: 100%!important;
}
.tag-nav-wrapper {
  display: none;
}
</style>
