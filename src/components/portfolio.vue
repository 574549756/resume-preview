<template>
  <div class="project">
    <div class="header">
      <h3>项目信息</h3>
      <div class="breakLine"></div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projectList[0]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <div class="stackIcon">
            <p>Canvas画板</p>
            <svg class="vue" aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projectIcons[4]}`"></use>
            </svg>
            <svg class="vue" aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projectIcons[2]}`"></use>
            </svg>
          </div>
          <div class="linkArea"><a href="">浏览链接</a><a href="">代码链接</a></div>
        </div>
        <p>Canvas画板，blablablabla</p>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        projectList: [
          'canvas.jpg',
          'nav-page.jpg',
          'slide.jpg'
        ],
        projectIcons:[
          'vuejs',
          'node-js',
          'jquery',
          'react',
          'html',
          'socialjavascript'
        ]
      }
    },
    methods: {},
    components: {}
  }
</script>

<style lang="scss">
  .project {
    margin: 10px 5vw 10px 3vw;
    .pro {
      display: flex;
      justify-content: space-between;
      align-items: space-between;
      .proDiscription {
        margin: 0 0 0 12px;
        .stack {
          width: 45vw;
          display: flex;
          justify-content: space-between;
          align-items: center;
          .stackIcon{
            display: flex;
            svg{
            width: 15px;
            height: 15px;
            }
          }
        }
      }
      p {
        font-size: 12px;
        color: #979695;
      }
      img {
        width: 100px;
        height: 75px;
      }
    }
    .header {
      display: flex;
      flex-direction: column;
      align-items: flex-start;
      margin: 15px 0 20px 0;
      h3 {
        color: black;
        margin: 0 0 10px 0;
      }
      .breakLine {
        align-self: center;
        background-color: #bcbcbe;
        height: 1px;
        margin: 0 0 0 0vw;
        width: 59vw;
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
  }
</style>