<template>
	<div>
		<div id="error">
			<div class="error_status">{{ error.statusCode }}</div>
			<div class="error_message">{{ error.message }}</div>
		</div>
	</div>
</template>

<script>
export default {
	props: ['error'],
	layout: 'error-layout'
}
</script>

<style>

</style>