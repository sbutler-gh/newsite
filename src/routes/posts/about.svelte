<script lang="ts">
	import Counter from '$lib/Counter.svelte';
	import HCard from '$lib/Hcard.svelte';
</script>

<svelte:head>
	<title>Hello about index!</title>
</svelte:head>

<main>
	<h1>Hello about index!</h1>

	<HCard />
	<!-- <Counter /> -->

	<p>Visit <a href="https://svelte.dev">svelte.dev</a> to learn how to build Svelte apps.</p>
</main>

<!-- Accessibility to keep in mind -->
<!-- https://perfectmotherfuckingwebsite.com/ -->
<!-- https://motherfuckingwebsite.com/ -->


<style>
	/* main {
		text-align: center;
		padding: 1em;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4rem;
		font-weight: 100;
		line-height: 1.1;
		margin: 4rem auto;
		max-width: 14rem;
	}

	p {
		max-width: 14rem;
		margin: 2rem auto;
		line-height: 1.35;
	}

	@media (min-width: 480px) {
		h1 {
			max-width: none;
		}

		p {
			max-width: none;
		}
	} */
</style>
