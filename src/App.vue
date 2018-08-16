<template>
<div id="app">
    <div class="header">这里是头</div>
    <div class="IdBoard">这里是名片卡
        <footer class="connection">这里是联系方式</footer>
    </div>
    <div class="edu">工作经历 自学前端半年</div>
    <div class="ability">这里是能力值
        <div>
    <p>1.小程序可以独立进行小程序开发，熟悉AAA、BBB、CCC相关API或组件的使用</p>
    <p>熟悉Vue常用功能如：组件、Vue-Router、双向绑定等</p>
    <p>jQuery 熟悉常用API，能使用jQuery制作网站、轮播、tab组件等</p>
    <p>HTML5 CSS3 独立制作精美网页，掌握CSS3动画、过渡效果、响应式等常用技术</p>
    <p>移动端页面 会使用rem、vw/vh、FastClick(去看看别人的博客) 等技术制作适配手机设备的页面</p>
        </div>
    </div>
    <div class="project">这里是项目 源码 预览 二维码(https://cli.im) 关键词 描述
      <p>scrollreveal js</p>
      <p>echarts</p>
      <p>particle js</p>
      <p>awesome javascript</p>
    </div>
</div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .header {
    height: 40px;
    width: 100%;
    background: #f8f8f8;
    position: absolute;
    top: 0;
  }
  .IdBoard {
    height: 300px;
    width: 100%;
    background: #f8f8f8;
  }
}
</style>
