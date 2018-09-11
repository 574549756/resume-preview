<template>
  <div class="IdBoard">
    <div class="header">
      <h3>个人信息</h3>
      <div class="breakLine"></div>
    </div>
    <div class="container">
      <div class="idDetail">
        <ul>
          <li>出生日期</li>
          <li>年龄</li>
          <li>城市</li>
        </ul>
        <ul class="msg">
          <li>1994.2.25</li>
          <li>24</li>
          <li>重庆</li>
        </ul>
      </div>
      <div class="idDetailRow2">
        <ul>
          <li>学历</li>
          <li>专业</li>
          <li>学校</li>
        </ul>
        <ul class="msg">
          <li>本科</li>
          <li>建筑学</li>
          <li>大连民族大学</li>
        </ul>
      </div>
    </div>
    <connection/>
  </div>
</template>


<script>
  import connection from './connection'
  export default {
    data() {
      return {}
    },
    components: {
      connection
    }
  }
</script>

<style lang="scss">
.IdBoard {
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    height: 35vw;
    width: 65vw;
    .container {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        margin: 10px 0 10px 0;
        .idDetailRow2 {
            display: flex;
            justify-content: center;
            align-items: center;
            margin: 0 0 20px 120px;
            ul {
                margin: 0 0 10px 3vw;
                display: flex;
                flex-direction: column;
                justify-content: flex-start;
                align-items: flex-start;
                color: #979695;
                li {
                    font-size: 15px;
                    margin: 2px 0;
                }
            }
            .msg {
                color: rgb(30, 30, 30);
            }
        }
        .idDetail {
            display: flex;
            justify-content: center;
            align-items: center;
            margin-bottom: 20px;
            ul {
                margin: 0 0 10px 3vw;
                display: flex;
                flex-direction: column;
                justify-content: flex-start;
                align-items: flex-start;
                color: #979695;
                li {
                    font-size: 15px;
                    margin: 2px 0;
                }
            }
            .msg {
                color: rgb(30, 30, 30);
            }
        }
    }
    .header {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        margin: 30px 0 20px 0;
        h3 {
            color: black;
            margin: 0 0 10px 3vw;
        }
        .breakLine {
            align-self: center;
            background-color: #bcbcbe;
            height: 1px;
            width: 70vw;
            margin-left: 3vw;
            z-index: 200;
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