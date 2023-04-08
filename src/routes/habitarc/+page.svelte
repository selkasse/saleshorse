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
	<meta name="twitter:image" content="https://i.imgur.com/J51tkuA.png" /> -->

	<!-- <meta property="og:title" content="Habit Arc" />
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
	<meta property="twitter:image" content="https://i.imgur.com/J51tkuA.png" /> -->

	<meta property="og:site_name" content="saleshorse blog" />
	<meta property="twitter:card" content="summary_large_image" /><link
		rel="preload"
		as="image"
		href="https://cdn.hashnode.com/res/hashnode/image/upload/v1677530759493/7404e96b-9f2d-4a64-8f8f-dc26cef48eff.png?w=400&amp;h=400&amp;fit=crop&amp;crop=faces&amp;auto=compress,format&amp;format=webp"
	/><meta name="description" content="- Log into Postman" />
	<meta property="og:title" content="How to Get a Salesforce Access Token with Postman" /><meta
		property="og:description"
		content="- Log into Postman"
	/><meta property="og:type" content="article" /><meta
		property="og:url"
		content="https://saleshorse.org/habitarc"
	/>
	<meta
		name="image"
		property="og:image"
		content="https://hashnode.com/utility/r?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1677558266929%2F6471cefa-5516-473b-9c11-52a77a6dfcb8.jpeg%3Fw%3D1200%26h%3D630%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp%26fm%3Dpng"
	/><meta
		property="twitter:title"
		content="How to Get a Salesforce Access Token with Postman"
	/><meta property="twitter:description" content="- Log into Postman- " /><meta
		property="twitter:image"
		content="https://hashnode.com/utility/r?url=https%3A%2F%2Fcdn.hashnode.com%2Fres%2Fhashnode%2Fimage%2Fupload%2Fv1677558266929%2F6471cefa-5516-473b-9c11-52a77a6dfcb8.jpeg%3Fw%3D1200%26h%3D630%26fit%3Dcrop%26crop%3Dentropy%26auto%3Dcompress%2Cformat%26format%3Dwebp%26fm%3Dpng"
	/>
	<link
		rel="preload"
		as="image"
		href="https://cdn.hashnode.com/res/hashnode/image/upload/v1677558266929/6471cefa-5516-473b-9c11-52a77a6dfcb8.jpeg?w=1600&amp;h=840&amp;fit=crop&amp;crop=entropy&amp;auto=compress,format&amp;format=webp"
	/>
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
