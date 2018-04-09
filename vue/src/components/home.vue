<template>
	<div class="home">
		<Wheader></Wheader>
		<div class="content">
			<left-mune></left-mune>
			<div class="pages">
				{{msg}}
			</div>
		</div>
	</div>
</template>

<script>
	import Wheader from "./header";
	import LeftMune from "./leftMune";
	
	export default {
	  	name: 'home',
	  	data () {
		    return {
		      msg: '222'
		    }
	  	},
	    components:{
	    	'Wheader' : Wheader,
	    	'left-mune' : LeftMune
	    }
	}
</script>

<style lang="less">
	@import '../style/css/common.css';
	.home{
		width:100%;
		height:auto;
	}
</style>
