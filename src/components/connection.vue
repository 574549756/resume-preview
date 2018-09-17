<template>
    <div class="connection">
        <div class="normal">
            <div class="github">
            <svg class="icon" aria-hidden="true">
                <use xlink:href="#icon-github"></use>
            </svg>
            <a href="https://github.com/574549756">https://github.com/574549756</a>
        </div>
        <div class="qq">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-qq"></use>
                </svg>
                <p>574549756</p>
            </div>
        </div>
        <div class="normal">
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
        </div>
        <div class="normal">
            <div class="blog">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-blog"></use>
                </svg>
                <a href="https://574549756.github.io/">https://574549756.github.io/</a>
            </div>
            <div class="wechat">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-wechat"></use>
                </svg>
                <p>z574549756</p>
            </div>
        </div>

    </div>
</template>

<style lang="scss">
.connection {
    margin-left: 200px;
    svg {
        fill: #f3f3f5;
        background: #f56c6c;
    }
    display: flex;
    flex-direction: column;
    .normal {
        margin: 0;
        .wechat {
            margin-left: 60px;
        }
        .qq {
            margin-left: 50px;
        }
        .phone {
            margin-left: 73px;
        }
    }
    div {
        margin: 3px 15px 6px 3px;
        display: flex;
        justify-content: flex-start;
        a {
            margin-left: 5px;
            font-size: 12px;
            color: #979695;
        }
        p {
            margin-left: 5px;
            font-size: 12px;
            color: #979695;
        }
    }
}
</style>