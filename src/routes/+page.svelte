<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>saleshorse</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1>
		<!-- TODO: find a cool font -->
		<a href="https://limey.io/saleshorse">saleshorse</a>
	</h1>

	<h2>
		Salesforce, with a bit of <strong>horsin' around</strong>
	</h2>

	<h3>giddy on up and take a look at the <a href="/habitarc">current project</a></h3>
	<h3>
		or get your fill of the salt lick over at <a href="https://blog.saleshorse.org">the blog</a>
	</h3>

	<!-- <Counter /> -->
</section>

<style>
	:global(section) {
		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
		flex: 0.6;
	}

	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
