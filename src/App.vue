<template>
    <div id="app">
        <div class="leftBar">
            <div class="photo"></div>
            <div class="mainTitle">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-gerenlogoBold"></use>
                </svg>
                <h1>张博涵</h1>
                <h2>前端工程师</h2>
            </div>
            <div class="edu"></div>
            <div class="skills">
                <radar/>
            </div>
            <abilityDiscription/>
            <onlinelink/>
        </div>
        <div class="rightSide">
            <idBoard/>
            <portfolio/>
            <experience/>
        </div>
    </div>
</template>

<script>
import onlinelink from "./components/onlinelink";
import radar from "./components/radar";
import idBoard from "./components/idBoard";
import experience from "./components/experience";
import abilityDiscription from "./components/abilityDiscription";
import portfolio from "./components/portfolio";
export default {
	name: "App",
	data() {
		return {};
	},
	components: {
		radar,
		idBoard,
		experience,
		abilityDiscription,
		portfolio,
		onlinelink
	}
};
</script>

<style lang="scss">
#app {
	font-family: "Avenir", Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	display: flex;
	flex-direction: row;
	.leftBar {
		display: flex;
		flex-direction: column;
		background: #424244;
		width: 33vw;
		height: 100%;
		.mainTitle {
			display: flex;
			flex-direction: column;
			justify-content: center;
			background: #ec5658c4;
			height: 10vw;
			width: 55vw;
			margin-top: -10vw;
			z-index: 10;
			padding-left: 3vw;
			svg {
				fill: #f3f3f5;
				width: 6vw;
				height: 6vw;
				position: absolute;
			}
			h1 {
				font-size: 35px;
				font-weight: 300;
				margin: 0 0 0 0;
				color: #f3f3f3;
			}
			h2 {
				font-size: 13px;
				color: #f3f3f3;
				margin: 0 0 0 0;
			}
		}
		.photo {
			background: rgb(100, 100, 105);
			width: 33vw;
			height: 33vw;
		}
	}
	.rightSide {
		background: #f3f3f5;
		width: 100%;
	}
}
</style>