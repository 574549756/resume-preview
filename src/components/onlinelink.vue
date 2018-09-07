<template>
    <div class="onlineLink">
        <div class="header">
            <h3>在线版简历</h3>
            <div class="breakLine"></div>
        </div>
        <div class="onlineMode">
            <a href="">Online Mode</a>
        </div>
    </div>
</template>

<style lang="scss">
.onlineLink {
    .header {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        margin: 25px 0 20px 0;
        h3 {
            color: white;
            margin: 0 0 10px 4vw;
        }
        .breakLine {
            align-self: center;
            background-color: #bcbcbe;
            height: 1px;
            width: 25vw;
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
    .onlineMode {
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 10px 0 30px 0;
        a {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 50px;
            width: 150px;
            font-size: 15px;
            font-weight: 700;
            color: white;
            border: 3px solid #bcbcbe;
            border-radius: 25px;
        }
    }
}
</style>
