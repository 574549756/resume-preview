<template>
    <div class="experience">
        <div class="header">
            <h3>工作经历</h3>
            <div class="breakLine"></div>
        </div>
        <div class="experienceDetail">
            <p>2017.3~2017.7 重庆孚思厅建筑规划设计有限公司 建筑师</p>
            <p>2017.7~2018.3 重庆赛薇汀文化创意有限公司 平面设计师</p>
            <p>2018.3~ 自学前端半年</p>
        </div>
    </div>
</template>

<script>
export default {
	data(){
		return{}
	},
	methods: {},
	components:{}
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
