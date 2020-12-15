<script>
	export let name;
</script>

<style lang="scss">
	h1 {
		color: purple;
		@media (max-width: 640px) {
			color: #000000;
		}
	}
</style>

<h1>Hello {name}!</h1>
