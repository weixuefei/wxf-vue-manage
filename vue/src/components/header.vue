<template>
	<div class="header clearfix">
		<img src="../style/images/logo.png" alt="logo" class="header-logo" />
		<div class="header-right">
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
			float:left;
			width:120px;
			margin-left: 10px;
		}
		.header-right{
			float:right;
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