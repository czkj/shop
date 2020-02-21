<template>
  <div id="app">
      <ul class="footer-bar">
        <li>首页</li>
        <li>分类</li>
        <li>购物车</li>
        <li>我的</li>
      </ul>
  </div>
</template>

<style lang="scss">
.footer-bar{
  padding: 0;
  margin: 0;
  padding-left: 30px;
  list-style-type: none;
  background-color:#eee;
  display: flex;
  position: fixed;
  bottom: 0;
  width: 100%;
  height: 50px;
  // flex-direction: row;
  
}
.footer-bar li{
  flex: 1;
  align-self:flex-end;
}

</style>
