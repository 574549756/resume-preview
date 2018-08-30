<template>
    <div class="connection">
        <div class="github">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-github"></use>
            </svg>
            <p>https://github.com/574549756</p>
        </div>
        <div class="gmail">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-gmail"></use>
            </svg>
            <p>ex.arc.zhang@gmail.com</p>
        </div>
        <div class="phone">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-1101dianhua"></use>
            </svg>
            <p>18640961725</p>
        </div>
        <div class="wechat">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-wechat"></use>
            </svg>
            <p>z574549756</p>
        </div>
        <div class="qq">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-qq"></use>
            </svg>
            <p>574549756</p>
        </div>
    </div>
</template>

<style lang="scss">
.connection {
  svg {
    fill: #f3f3f5;
    background: #f56c6c;
  }
  display: flex;
  flex-direction: column;
  div {
    margin: 3px;
    display: flex;
    p {
      font-size: 12px;
      color: #979695;
    }
  }
}
</style>
