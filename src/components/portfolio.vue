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
          <a href="https://574549756.github.io/canvas/index.html">浏览链接</a>
          <a href="https://github.com/574549756/canvas">代码链接</a>
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
          <a href="https://574549756.github.io/myBookmarks/nav-demo/index.html">浏览链接</a>
          <a href="https://github.com/574549756/myBookmarks">代码链接</a>
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
          <a href="https://574549756.github.io/Jquery-slide/index.html">浏览链接</a>
          <a href="https://github.com/574549756/Jquery-slide">代码链接</a>
        </div>
      </div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[4]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[4]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[0]}`"></use>
            </svg>
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[5]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[4]}}</p>
        <div class="linkArea">
          <a href="https://574549756.github.io/cssBatman/">浏览链接</a>
          <a href="https://github.com/574549756/cssBatman">代码链接</a>
        </div>
      </div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[3]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[3]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[0]}`"></use>
            </svg>
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[5]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[3]}}</p>
        <div class="linkArea">
          <a href="https://574549756.github.io/vue-resumer-demo/dist/index.html">浏览链接</a>
          <a href="https://github.com/574549756/vue-resumer-demo">代码链接</a>
        </div>
      </div>
    </div>
    <div class="pro">
      <img v-bind:src="`/static/img/${projects.projectImg[3]}`" alt="">
      <div class="proDiscription">
        <div class="stack">
          <p>{{projects.projectName[3]}}</p>
          <div class="stackIcon">
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[0]}`"></use>
            </svg>
            <svg aria-hidden="true">
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[4]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[5]}`"></use>
            </svg>
            <svg aria-hidden="true" >
              <use v-bind:xlink:href="`#icon-${projects.projectIcons[6]}`"></use>
            </svg>
          </div>
        </div>
        <p>{{projects.projectDis[3]}}</p>
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
          'slide.jpg',
          'vueResume.png',
          'cssBatman.png'
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
            '无缝轮播组件',
            'Vue简历编辑器',
            'CSS蝙蝠侠'
          ],
          projectDis: [
            'Canvas画板，通过使用 Canvas API 实现画板的:画笔、橡皮擦、更改颜色、清屏、保存等功能。',
            '这是个键盘，拿来存网站导航的，原生 JS 监听键盘事件。通过favicon获取网站图标，通过　favicon.byi.pw?url=domain　排除无法获取的网站图标',
            '通过 settimeout 实现自动轮播，改变 class　状态机的方式来改变监听事件。',
            '通过 Vue 实现数据绑定',
            '使用 CSS3 绘制蝙蝠侠，通过 settimeout 实现代码逐个显示，绘制蝙蝠侠的过程'
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
        padding: 5px;
        background: #f2f2f3;
        box-shadow: 0 0 10px 0 rgba(0, 0, 0, 0.1);
        border-radius: 5px;
        .proDiscription {
            margin: 0 0 0 12px;
            position: relative;
            width: 50vw;
            > p {
                margin: 5px 0;
                width: 50vw;
                text-align: left;
                word-break: break-all;
                word-wrap: break-word;
            }
            .stack {
                width: 50vw;
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
        margin: 15px 0 30px 0;
        h3 {
            color: black;
            margin: 0 0 10px 0;
        }
        .breakLine {
            align-self: center;
            background-color: #bcbcbe;
            height: 1px;
            width: 70vw;
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