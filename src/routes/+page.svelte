<script lang="ts">
	import Cards from './Cards.svelte';

	const videoCards = [
		{ title: 'The Roku Channel', url: 'http://therokuchannel.roku.com' },
		{ title: 'Pluto TV', url: 'https://pluto.tv' },
		{ title: 'React TV', url: 'https://react.tv/catalog' }
	];
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Visual media" />
</svelte:head>

<section>
	<h1>Video</h1>

	<h2>Film, tv and visual media</h2>

	<Cards cards={videoCards} />
</section>

<style>
</style>
