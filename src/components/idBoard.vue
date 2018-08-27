<template>
<div class="IdBoard">
  <div class="header">
      <h3>个人信息</h3>
      <div class="breakLine"></div>
    </div>
      <div class="idDetail">
        <ul>
          <li>姓名</li>
          <li>出生日期</li>
          <li>城市</li>
          <li>学历</li>
        </ul>
        <ul>
          <li>张博涵</li>
          <li>1994.2.25</li>
          <li>重庆</li>
          <li>本科</li>
        </ul>
      </div>
    </div>    
</template>

<script>
export default {}
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
      margin: 0 0 10px 2vw;
    }
    .breakLine {
      align-self: center;
      background-color: #5c5b5c;
      height: 2px;
      width: 59vw;
      margin-left: 2vw;
      z-index: 100;
      &::before {
        display: block;
        content: '';
        align-self: flex-start;
        background: #f56c6c;
        height: 2px;
        width: 4.25vw;
      }
    }
  }
  .idDetail {
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    ul {
      display: flex;
      flex-direction: column;
    }
  }
}
</style>
