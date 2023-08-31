<script>
	import Header from '../lib/Header.svelte';
</script>

<h1 class="p-4 font-bold roboto text-4xl flex justify-center">Welcome to JSAL.org</h1>
<p class="p-1 roboto text-2xl flex justify-center">
	The onofficial hub for the JackSucksAtLife empire!
</p>
<div class="grid place-items-center grid-cols-2">
	<a
		href="https://wiki.jsal.org"
		class="roboto text-2xl flex justify-center group relative transition-all duration-300 ease-in-out hover:scale-110 bg-black"
	>
		<img src="/wiki.png" alt="wiki" class="griditem hover:opacity-50" />
		<h2
			class=" text-white roboto text-2xl opacity-0 group-hover:opacity-100 font-bold absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 pointer-events-none transition-all duration-300 ease-in-out"
		>
			Wiki
		</h2></a
	>
	<a
		href="https://memes.jsal.org"
		class="roboto text-2xl flex justify-center group relative transition-all duration-300 ease-in-out hover:scale-110 bg-black"
	>
		<img src="/memes.png" alt="memes" class="griditem hover:opacity-50" />
		<h2
			class=" text-white roboto text-2xl opacity-0 group-hover:opacity-100 font-bold absolute top-1/2 left-1/2 -translate-x-1/2 -translate-y-1/2 pointer-events-none transition-all duration-300 ease-in-out"
		>
			Memes
		</h2>
	</a>
</div>

<style>
	.roboto {
		font-family: 'Roboto', sans-serif;
	}
	.griditem {
		max-width: 800px;
	}
</style>
