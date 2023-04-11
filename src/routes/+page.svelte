<svelte:head>
	<title>saleshorse</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<h1 class="title">
		<!-- TODO: find a cool font -->
		<a href="https://limey.io/saleshorse">saleshorse</a>
	</h1>

	<p class="subtext">
		Salesforce, with a bit of <strong>horsin' around</strong>
	</p>

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
</style>
