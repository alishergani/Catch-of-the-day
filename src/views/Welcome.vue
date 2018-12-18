<template>
	<div class="page welcome">
		<h1>Welcome</h1>
		<form action="" @submit.prevent="goToMain">
			<input type="text" name="secret" v-model="secret">
			<button type="submit">login</button>
		</form>
	</div>
</template>

<script>
export default {
	name: 'welcome',
	data() {
		return {
			secret: ''
		}
	},
	methods: {
		goToMain(e) {
			this.$router.push(`/main/${this.secret}`)
		}
	}
}
</script>