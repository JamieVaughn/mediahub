<script lang="ts">
	import Cards from '../Cards.svelte';

	const audioCards = [{ title: 'Book Audio Book', url: 'https://bookaudiobook.net/' }];
</script>

<svelte:head>
	<title>Audio</title>
	<meta name="description" content="Audio media" />
</svelte:head>

<section>
	<h1>Audio</h1>

	<h2>Audiobooks and podcasts</h2>

	<Cards cards={audioCards} />
</section>
