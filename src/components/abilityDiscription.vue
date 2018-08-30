<template>
    <div class="ability">
        <div class="header">
            <h3>技能描述</h3>
            <div class="breakLine"></div>
        </div>
        <div class="skillsDetail">
            <p>1.小程序可以独立进行小程序开发，熟悉AAA、BBB、CCC相关API或组件的使用</p>
            <p>熟悉Vue常用功能如：组件、Vue-Router、双向绑定等</p>
            <p>jQuery 熟悉常用API，能使用jQuery制作网站、轮播、tab组件等</p>
            <p>HTML5 CSS3 独立制作精美网页，掌握CSS3动画、过渡效果、响应式等常用技术</p>
            <p>移动端页面 会使用rem、vw/vh、FastClick(去看看别人的博客) 等技术制作适配手机设备的页面</p>

        </div>
        <div class="project">这里是项目 源码 预览 二维码(https://cli.im) 关键词 描述
            <p>scrollreveal js</p>
            <p>echarts</p>
            <p>particle js</p>
            <p>awesome javascript</p>
        </div>
    </div>
</template>

<style lang="scss">
.ability {
  .skillsDetail {
    padding: 0 3vw 0 4vw;
  }
  .header {
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin: 30px 0 20px 0;
    h3 {
      color: white;
      margin: 0 0 10px 4vw;
    }
    .breakLine {
      align-self: center;
      background-color: #bcbcbe;
      height: 1px;
      width: 25vw;
      z-index: 100;
      position: relative;

      &::before {
        position: absolute;
        top: -1px;
        display: block;
        content: '';
        align-self: flex-start;
        background: #f56c6c;
        height: 3px;
        width: 4.25vw;
      }
    }
  }
  p {
    color: white;
  }
}
</style>
