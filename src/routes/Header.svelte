<script>
	import { page } from '$app/stores';
	import logo from '$lib/images/svelte-logo.svg';
	// import github from '$lib/images/github.svg';
	import horse from '$lib/images/horse.svg';
	import horseshoe from '$lib/images/horseshoe.svg';
</script>

<header>
	<!-- TODO: change to horse emoji -->
	<div class="corner">
		<a href="/">
			<img src={horse} alt="horse" />
		</a>
	</div>

	<div class="corner">
		<!-- TODO: change to link to contact/social card -->

		<a href="https://limey.io/saleshorse/">
			<img src={horseshoe} alt="horseshoe" />
		</a>
	</div>
</header>

<style>
	header {
		display: flex;
		justify-content: space-between;
	}

	.corner {
		width: 3em;
		height: 3em;
	}

	.corner a {
		display: flex;
		align-items: center;
		justify-content: center;
		width: 100%;
		height: 100%;
	}

	.corner img {
		width: 2em;
		height: 2em;
		object-fit: contain;
	}

	a:hover {
		color: var(--color-theme-1);
	}
</style>
