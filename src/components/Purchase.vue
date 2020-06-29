<template>
	<div class="page">
	<h2>结算<br /></h2>
		<h4>需要支付:</h4>
		{{this.$route.query.total}}元	
		<h4>支付成功！</h4>
		<button @click="$router.push('/')">返回</button>
		</div>
		
</template>

<script>
	
</script>

<style>
</style>
