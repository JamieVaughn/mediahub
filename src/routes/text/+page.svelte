<script lang="ts">
	import Cards from '../Cards.svelte';

	const textCards = [
		{ title: 'Free Novel Read', url: 'https://freenovelread.com/' },
		{ title: 'Project Gutenberg', url: 'https://www.gutenberg.org/' },
		{ title: 'Stay Blessed Stay Humble', url: 'https://stayblessedstayhumble.org/' }
	];
</script>

<svelte:head>
	<title>Text</title>
	<meta name="description" content="Text media" />
</svelte:head>

<section>
	<h1>Text</h1>

	<h2>Books and articles</h2>

	<Cards cards={textCards} />
</section>
