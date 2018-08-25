<template>
<div class="IdBoard">
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
  flex-direction: row;
  justify-content: center;
  align-items: flex-start;
  height: 35vw;
  width: 65vw;
  background: #f8f8f8;

  .photo {
    width: 150px;
    height: 200px;
    background: black;
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
