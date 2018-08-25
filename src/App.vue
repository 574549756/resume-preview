<template>
  <div id="app">
    <div class="leftBar">
      <div class="photo"></div>
      <div class="mainTitle">
        <svg class="icon" aria-hidden="true">
          <use xlink:href="#icon-gerenlogoBold"></use>
        </svg>
        <h1>张博涵</h1>前端工程师</div>
      <div class="edu"></div>
      <div class="skills">
        <h2>SKILLS</h2>
        <div class="headerline"></div>
        <radar/>
      </div>
    </div>
    <div class="rightSide">
      <idBoard/>
      <div class="ability">

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
  </div>
</template>

<script>
import radar from './components/radar'
import idBoard from './components/idBoard'
export default {
  name: 'App',
  data() {
    return {}
  },
  components: {
    radar,
    idBoard
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  display: flex;
  flex-direction: row;
  .leftBar {
    display: flex;
    flex-direction: column;
    background: #424244;
    width: 35vw;
    height: 100vh;
    .mainTitle {
      display: flex;
      background: #f56c6ca4;
      height: 9vw;
      width: 55vw;
      margin-top: -9vw;
      z-index: 10;
      svg {
        fill: #f3f3f5;
        width: 6vw;
        height: 6vw;
        position: absolute;
      }
      h1 {
        font-size: 20px;
      }
    }
    .photo {
      background: green;
      width: 35vw;
      height: 35vw;
    }
  }
  .rightSide {
    background: #f3f3f5;
  }
}
</style>
