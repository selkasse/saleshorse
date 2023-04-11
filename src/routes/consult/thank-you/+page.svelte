<script>
	import { page } from '$app/stores';

	const url = $page.url;

	let firstName = url.searchParams.get('firstName');
</script>

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
