<script lang="ts">
	import Cards from '../Cards.svelte';

	const audioCards = [
		{ title: 'Book Audio Book', url: 'https://bookaudiobook.net/' },
		{ title: 'Book Search Party', url: 'https://booksearch.party/' },
		{ title: 'Spotify', url: 'https://spotify.com' },
		{ title: 'NPR One', url: 'https://one.npr.org/' },
		{ title: 'LibriVox', url: 'https://librivox.org/' },
		{ title: 'Shared Audiobooks', url: 'https://sharedaudiobooks.com' }
	];
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
