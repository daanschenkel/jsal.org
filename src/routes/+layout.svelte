<script>
	import '../app.postcss';
	import Header from '$lib/Header.svelte';
</script>

<Header />
<div class="body">
	<slot />
</div>

<style>
	.body {
		background-color: #eeeeee;
		min-height: calc(100vh - 80px);
	}
</style>
