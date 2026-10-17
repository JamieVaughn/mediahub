<script lang="ts">
	import Cards from './Cards.svelte';

	const videoCards = [
		{ title: 'The Roku Channel', url: 'http://therokuchannel.roku.com' },
		{ title: 'Pluto TV', url: 'https://pluto.tv' },
		{ title: 'React TV', url: 'https://react.tv/catalog' },
		{ title: 'Roku Channel Store', url: 'https://channelstore.roku.com/browse' },
		{
			title: 'Cord Cutters News',
			url: 'https://cordcuttersnews.com/how-to-watch-hundreds-of-live-tv-channels-for-free-legally-without-cable-tv/'
		},
		{ title: 'FMHY', url: 'https://fmhy.net/' },
		{ title: 'Amazon Freevee', url: 'https://www.amazon.com/freevee' },
		{ title: 'YouTube', url: 'https://youtube.com' },
		{ title: 'CuriosityStream', url: 'https://curiositystream.com/' },
		{ title: 'Nebula', url: 'https://nebula.tv' },
		{ title: 'Sensical', url: 'https://www.sensical.tv/', footer: 'For kids' }
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
