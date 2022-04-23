<script context="module" lang="ts">
	export const prerender = true;
</script>

<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import Nav from '$lib/Nav.svelte';
</script>

<svelte:head>
	<title>Home</title>
</svelte:head>

<section class="bg-gradient-to-r from-sky-500 to-blue-500">
	<Nav />
	<header class="flex flex-col min-h-screen text-center justify-center items-center bg-gradient-to-r from-sky-500 to-blue-500">
		<h1 class="my-10 text-9xl text-white font-bold">
			Hello World 👋
		</h1>		
		
		<h2 class="text-2xl text-white font-bold">
			Made with Svelte
		</h2>
		<Counter />

		<!-- <a href="about" class="font-semibold text-white my-1 bg-slate-400 rounded-md w-32">My Website 👉</a> -->
	</header>	
</section>