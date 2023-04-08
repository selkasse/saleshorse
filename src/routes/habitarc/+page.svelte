<svelte:head>
	<title>habit arc</title>
	<meta http-equiv="Content-type" content="text/html; charset=UTF-8" />
	<meta name="description" content="A habit archive; see the arc of your habit's data over time" />

	<!-- <meta name="twitter:card" content="summary_large_image" />
	<meta name="twitter:site:id" content="@saleshorseorg" />
	<meta name="twitter:creator" content="@saleshorseorg" />
	<meta name="twitter:title" content="habit arc" />
	<meta
		name="twitter:description"
		content="A habit archive; see the arc of your habit's data over time"
	/>
	<meta name="twitter:image" content="https://i.imgur.com/2apfaYsh.png" /> -->
	<meta property="og:title" content="Habit Arc" />
	<meta
		property="og:description"
		content="A habit archive; see the arc of your habit's data over time"
	/>
	<meta property="og:site_name" content="saleshorse" />
	<meta property="og:type" content="article" />
	<meta property="og:url" content="https://saleshorse.org/habitarc" />
	<meta name="image" property="og:image" content="https://i.imgur.com/J51tkuA.png" />

	<meta property="twitter:card" content="summary_large_image" />
	<meta property="twitter:title" content="Habit Arc" />

	<meta
		property="twitter:description"
		content="A habit archive; see the arc of your habit's data over time"
	/>
	<meta property="twitter:image" content="https://i.imgur.com/J51tkuA.png" />
</svelte:head>

<div class="text-column">
	<h1>habit arc</h1>

	<h3>⌚ track your health-related habits over time</h3>
	<h3>✅ see what works, and what doesn't — through the lens of your own data</h3>
	<h3>📝 log meals against an ever-growing, community-sourced database</h3>

	<h2 class="interested">interested?</h2>
	<p class="subtext">
		fill out this quick contact form, and we'll email you when it's time to
		<strong>saddle up</strong>
	</p>
	<form
		action="https://webto.salesforce.com/servlet/servlet.WebToLead?encoding=UTF-8"
		method="POST"
		class="form"
	>
		<input type="hidden" name="oid" value="00D8Y000001Qcn8" />
		<input type="hidden" name="retURL" value="https://saleshorse.org/habitarc/thank-you" />

		<label for="first_name">first name</label><input
			id="first_name"
			maxlength="40"
			name="first_name"
			size="20"
			type="text"
		/><br />

		<label for="last_name">last name</label><input
			id="last_name"
			maxlength="80"
			name="last_name"
			size="20"
			type="text"
		/><br />

		<label for="email">email</label><input
			id="email"
			maxlength="80"
			name="email"
			size="20"
			type="text"
		/><br />

		<input type="submit" name="submit" class="submit" value="submit" />
	</form>
</div>

<style>
	h1,
	h2 {
		color: var(--color-theme-1);
	}
	h3 {
		text-align: left;
	}
	.interested {
		margin-top: 5vh;
	}
	.subtext {
		font-size: 1.1em;
	}
</style>
