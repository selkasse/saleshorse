<script>
	import { page } from '$app/stores';

	const url = $page.url;

	let email = url.searchParams.get('invitee_email');
	let name = url.searchParams.get('invitee_full_name');
	let firstName = name?.substring(0, name.indexOf(' '));
	let lastName = name?.substring(name.indexOf(' ') + 1);

	// let BASE_URL = `https://b5ae-2600-4040-4751-3e00-f037-6e12-306f-5051.ngrok-free.app`;
	let BASE_URL = `https://saleshorse.org`;

	let returnURL = `${BASE_URL}/consult/thank-you?firstName=${firstName}`;

	/**
	 * @type {HTMLInputElement}
	 */
	export let submitButton;

	$: {
		clickButton(submitButton);
	}

	/**
	 * @param {HTMLInputElement} button
	 */
	function clickButton(button) {
		if (button) {
			button.click();
		}
	}
</script>

<svelte:head>
	<title>thank you!</title>
	<meta name="description" content="Consult redirect page" />
</svelte:head>

<section>
	<div class="text-column">
		<h1>looking forward to speaking with you, <span>{firstName}!</span></h1>
	</div>
</section>

<form
	action="https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8"
	method="POST"
	class="form"
>
	<input type="hidden" name="oid" value="00D8Y000001Qcn8" />
	<input type="hidden" name="retURL" value={returnURL} />
	<input type="hidden" name="ProductInterest__c" value="CONS" />
	<input type="hidden" name="first_name" value={firstName} />
	<input type="hidden" name="last_name" value={lastName} />
	<input type="hidden" name="email" value={email} />

	<input
		bind:this={submitButton}
		type="submit"
		name="submit"
		style="display: none"
		value="submit"
	/>
</form>

<style>
	span {
		color: var(--color-theme-1);
	}
</style>
