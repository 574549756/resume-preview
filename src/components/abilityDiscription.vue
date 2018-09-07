<template>
	<div class="ability">
		<div class="header">
			<h3>技能描述</h3>
			<div class="breakLine"></div>
		</div>
		<div class="skillsDetail">
			<!-- <p>1.小程序可以独立进行小程序开发，熟悉AAA、BBB、CCC相关API或组件的使用</p> -->
			<div class="Vue">
				<svg class="vue" aria-hidden="true">
					<use xlink:href="#icon-vuejs"></use>
				</svg>
				<p>熟悉Vue常用功能如：组件、Vue-Router、双向绑定、数据响应原理等</p>
			</div>
			<div class="js">
				<svg class="javascript" aria-hidden="true">
					<use xlink:href="#icon-socialjavascript"></use>
				</svg>
				<p>在不使用框架的前提下能够使用原生 JS 常用 API 完成部分需求。熟悉 jQuery 常用API，能使用jQuery制作网站、轮播、tab组件等</p>
			</div>
			<div class="html">
				<svg class="html" aria-hidden="true">
					<use xlink:href="#icon-html"></use>
				</svg>
				<p>熟练编写语义化 HTML 能使用 HTML5 CSS3 独立制作精美网页，掌握CSS3动画、过渡效果、响应式等常用技术</p>
			</div>
			<div class="css">
				<svg class="css" aria-hidden="true">
					<use xlink:href="#icon-language-css"></use>
				</svg>
				<p>移动端页面 会使用 rem、vw/vh 等技术制作适配手机设备的页面，能够在项目中使用 Scss 预处理工具</p>
			</div>
			<div class="http">
				<svg class="http" aria-hidden="true">
					<use xlink:href="#icon-http"></use>
				</svg>
				<p>了解 HTTP 基础知识，了解常见状态码的含义，能够根据请求查看响应。</p>
			</div>
			<div class="node">
				<svg class="node" aria-hidden="true">
					<use xlink:href="#icon-node-js"></use>
				</svg>
				<p>了解 Node.js 的一些知识，能够使用 Node.js 搭建小型服务器，根据请求的 URL 返回指定数据。</p>
			</div>

		</div>
	</div>
</template>

<style lang="scss">
.ability {
    .skillsDetail {
        padding: 0 3vw 0 4vw;
        p {
            font-size: 12px;
            color: #f2f2f3;
            text-align: left;
            word-break: break-all;
            word-wrap: break-word;
            margin-left: 40px;
        }
        div {
            margin: 10px 0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            svg {
                position: absolute;
                width: 26px;
                height: 26px;
                fill: #f2f2f3;
                background: #f56c6c;
                border-radius: 13px;
                border: 3px solid #f56c6c;
            }
        }
    }
    .header {
        display: flex;
        flex-direction: column;
        align-items: flex-start;
        margin: 30px 0 20px 0;
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
    p {
        color: white;
    }
}
</style>