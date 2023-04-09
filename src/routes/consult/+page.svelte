<script>
	let queryString = window.location.search;
	let urlParams = new URLSearchParams(queryString);
	let email = urlParams.get('invitee_email');
	let name = urlParams.get('invitee_full_name');
	console.log(`email: ${email}`);
	console.log(`name: ${name}`);
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
