<template>
    <div class="experience">
        <div class="header">
            <h3>工作经历</h3>
            <div class="breakLine"></div>
        </div>
        <div class="experienceDetail">
            <div class="firstExp">
                <header>
                    <h1>建筑师</h1>
                    <h2>2017.3~2017.7</h2>
                </header>
                <main>
                    <h2>重庆孚思厅建筑规划设计有限公司</h2>
                    <p>建筑方案设计，投标方案，效果图绘制，建筑模型制作</p>
                </main>
            </div>
            <div class="secondExp">
                <header>
                    
                    <h1>平面设计师</h1>
                    <h2>2017.7~2018.3</h2>
                </header>
                <main>
                    <h2>重庆赛薇汀文化创意有限公司</h2>
                    <p>宣传图制作、排版、拍摄</p>
                </main>
            </div>
            <div class="thirdExp">
                <header>
                    <h1>自学</h1>
                    <h2>2018.3~</h2>
                </header>
                <main>
                    <h2>自学前端半年</h2>
                    <p></p>
                </main>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        },
        methods: {},
        components: {}
    }
</script>


<style lang="scss">
.experience {
    p {
        font-size: 12px;
        color: #979695;
    }
    .experienceDetail {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        padding: 0 10px 10px 3vw;
        .firstExp,
        .secondExp,
        .thirdExp {
            align-items: flex-start;
            display: flex;
            flex-direction: row;
            justify-content: space-around;
            margin: 10px 0;
            padding-bottom: 1px;
            > header {
                margin: 0 30px 0 0;
                display: flex;
                flex-direction: column;
                justify-content: flex-start;
                align-items: flex-end;
                width: 10vw;
                > h1 {
                    display: block;
                    margin: 2px 0;
                    font-size: 15px;
                    text-align: right;
                }
                > h2 {
                    display: block;
                    margin: 2px 0;
                    font-size: 12px;
                    text-align: right;
                    color: #979695;
                }
            }
            > main {
                margin: 0 0 0 30px;
                display: flex;
                flex-direction: column;
                justify-content: flex-start;
                align-items: flex-start;
                width: 50vw;
                > h2 {
                    margin: 2px 0;
                    font-size: 15px;
                    text-align: left;
                }
                > p {
                    margin: 2px 0;
                    font-size: 12px;
                    text-align: left;
                    color: #979695;
                }
            }
        }
    }
    .header {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        margin: 15px 0 20px 3vw;
        h3 {
            color: black;
            margin: 0 0 10px 0;
        }
        .breakLine {
            align-self: flex-start;
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