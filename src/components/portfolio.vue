<template>
  <div class="project">
    <div class="header">
      <h3>项目信息</h3>
      <div class="breakLine"></div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[0]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[0]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[5]}`"></use>
            </svg>
            <svg aria-hidden="true" style="width: 14px;height:14px;">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[2]}`"></use>
            </svg>
            <svg aria-hidden="true" style="width: 14px;height:14px;">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[0]}}</p>
        <div class="linkArea">
          <a href="">浏览链接</a>
          <a href="">代码链接</a>
        </div>
      </div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[1]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[1]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[5]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[1]}}</p>
        <div class="linkArea">
          <a href="">浏览链接</a>
          <a href="">代码链接</a>
        </div>
      </div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[2]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[2]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[2]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[2]}}</p>
        <div class="linkArea">
          <a href="">浏览链接</a>
          <a href="">代码链接</a>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
  export default {
    data() {
      return {
        projects: {
          projectImg: [
          'canvas.jpg',
          'nav-page.jpg',
          'slide.jpg'
        ],
          projectIcons: [
            'vuejs',
            'node-js',
            'jquery',
            'react',
            'html',
            'language-css',
            'socialjavascript'
          ],
          projectName: [
            'Canvas画板',
            'KeyBoard导航页',
            '无缝轮播组件'
          ],
          projectDis: [
            'Canvas画板，blablablabla叽里呱啦叽里呱啦叽里呱啦blablablablablablablablaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaaa',
            '这是个键盘，拿来存网站导航的，原生 JS 监听键盘事件。通过favicon获取网站图标，通过　favicon.byi.pw?url=domain　排除无法获取的网站图标',
            '通过 settimeout 实现自动轮播，改变 class　状态机的方式来改变监听事件。'
          ]
        }
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
        margin: 20px 0;
        display: flex;
        justify-content: space-between;
        align-items: space-between;
        .proDiscription {
            margin: 0 0 0 12px;
            position: relative;
            width: 45vw;
            > p {
                margin: 5px 0;
                width: 45vw;
                text-align: left;
                word-break: break-all;
                word-wrap: break-word;
            }
            .stack {
                width: 45vw;
                display: flex;
                justify-content: space-between;
                align-items: center;
                p {
                    font-size: 15px;
                    color: #424244;
                }
                .stackIcon {
                    display: flex;
                    svg {
                        margin: 0 3px;
                        width: 15px;
                        height: 15px;
                    }
                }
            }
            .linkArea {
                position: absolute;
                right: 0;
                bottom: 0;
            }
        }
        p {
            font-size: 12px;
            color: #979695;
        }
        img {
            border-radius: 5px;
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