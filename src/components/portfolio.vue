<template>
    <div class="project">
        <div class="header">
      <h3>项目信息</h3>
      <div class="breakLine"></div>
    </div>
    </div>
</template>

<style lang="scss">
.project {
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
