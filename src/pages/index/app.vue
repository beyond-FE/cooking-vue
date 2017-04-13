<template>
	<div>
	<h1>
		<img src="http://cn.vuejs.org/images/logo.png" alt="">
		<p>Hello,welcome to use Vue.js</p>
		<Vinput></Vinput>
	</h1>
	</div>
</template>
<script>
import Vinput from 'components/vinput.vue';

export default {
	components:{
		Vinput
	}
}	
</script>
<style>
	h1{
		color: #666666;
		margin: 15% auto;
		text-align: center;
		font-family: arial;
		font-weight: 500;
	}
	img{
		width:200px;
	}
</style>