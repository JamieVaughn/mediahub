<script lang="ts">
	type Card = {
		title: string;
		url: string;
	};

	let { cards = [] }: { cards?: Card[] } = $props();
</script>

<div class="cardlist">
	{#each cards as card (card.url)}
		<div class="card">
			<h2><a href={card.url}>{card.title}</a></h2>
		</div>
	{/each}
</div>

<style>
	.cardlist {
		display: grid;
		gap: 1rem;
		grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
	}
	.card {
		padding: 1rem;
		border-radius: 4px;
		box-shadow: 2px 2px 10px lab(10% 10% 10% / 0.5);
	}
</style>
