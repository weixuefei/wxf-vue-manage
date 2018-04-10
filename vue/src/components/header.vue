<template>
	<div class="header clearfix">
		<img src="../style/images/logo.png" alt="logo" class="header-logo l" />
		<span class="header-title l">xxxxxxxx</span>
		<div class="header-right r">
			<span class="name">张国荣</span>
			<i></i>
		</div>
	</div>
</template>

<script>
	export default {
        
    }
</script>

<style scoped lang="less">
	.header{
		width:100%;
		height:auto;
		border-bottom:1px solid #eee;
		padding:10px 0;
		.header-logo{
			width:120px;
			margin:0 10px 0 10px;
		}
		.header-title{
			display: inline-block;
			width:auto;
			height:auto;
			font-size:18px;
			color:#333;
		}
		.header-right{
			margin-right: 10px;
			.name{
				display: inline-block;
				width:auto;
				height:auto;
				line-height: 30px;
				color:#666;
			}
		}
	}
</style>