<script>
	// import { browser } from '$app/environment';
	import { page } from '$app/stores';

	// let queryString = window.location.search;
	// let urlParams = new URLSearchParams(queryString);
	// let email = urlParams.get('invitee_email');
	// let name = urlParams.get('invitee_full_name');

	// ;

	console.log(`email: ${$page.url.searchParams.get('invitee_email')}`);
	console.log(`name: ${$page.url.searchParams.get('invitee_full_name')}`);
	// if (browser) {
	// }
</script>

<svelte:head>
	<title>thank you!</title>
	<meta name="description" content="Consult thank-you page" />
</svelte:head>

<section>
	<div class="text-column">
		<h1><span>looking forward</span> to speaking with you!</h1>
	</div>
</section>

<style>
	span {
		color: var(--color-theme-1);
	}
</style>
