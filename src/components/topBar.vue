<template>
    <div>
        <div class='topbar'>
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-gerenlogoBold"></use>
            </svg>
            <div class="option">
                <ul>
                    <li>名片</li>
                    <li>联系方式</li>
                    <li>技能</li>
                    <li>作品</li>
                </ul>
            </div>
        </div>
    </div>
</template>

<style lang="scss">
.topbar {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: center;
  .icon {
    width: 40px;
    height: 40px;
    margin: 8px;
  }
  .option {
    display: flex;
    align-items: center;
    ul {
      display: flex;
      align-items: center;
      height: 50px;
      margin: 0;
      li {
        margin: 20px;
      }
    }
  }
}
</style>
