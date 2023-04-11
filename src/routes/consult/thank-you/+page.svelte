<script>
	import { page } from '$app/stores';

	const url = $page.url;

	let firstName = url.searchParams.get('firstName');
</script>

<svelte:head>
	<title>thank you!</title>
	<meta name="description" content="Consult thank you page" />
</svelte:head>
<section>
	<div class="text-column">
		<h1>looking forward to speaking with you, <span>{firstName}!</span></h1>
	</div>
</section>

<style>
	span {
		color: var(--color-theme-1);
	}
</style>
