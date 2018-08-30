<template>
  <div class="IdBoard">
    <div class="header">
      <h3>个人信息</h3>
      <div class="breakLine"></div>
    </div>
    <div class="idDetail">
      <ul>
        <li>出生日期</li>
        <li>城市</li>
        <li>学历</li>
        <li>专业</li>
        <li>学校</li>
      </ul>
      <ul>
        <li>1994.2.25</li>
        <li>重庆</li>
        <li>本科</li>
        <li>建筑学</li>
        <li>大连民族大学</li>
      </ul>
    </div>
    <connection/>
  </div>
</template>


<script>
import connection from './connection'
export default {
  data() {},
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
      width: 59vw;
      margin-left: 3vw;
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
        font-size: 14px;
      }
    }
  }
}
</style>
