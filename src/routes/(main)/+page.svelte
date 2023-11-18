<script>
	import Card from "../../lib/components/Card.svelte";
let currentTile;
</script>
<!-- ShowCase Container -->
<div class="variant-filled-tertiary">
	<!-- Heading with see more button -->
	<div class="p-2 flex justify-between text">
		<h2 class="h2">Top Rated Playlists</h2>
		<button class="opacity-60">See All</button>
	</div>
	<h3 class="p-2 h3">Folk</h3>
	<!-- Card Container -->
	
	<div class="grid sm:grid-cols-2 p-2 gap-2 lg:grid-cols-3 xl:grid-cols-5">
		<Card />
		<Card />
		<Card />
		<Card />
		<Card />
	</div>
	<h3 class="p-2 h3">Alternative</h3>
	<!-- Card Container -->
	<div class="grid sm:grid-cols-2 p-2 gap-2 lg:grid-cols-3 xl:grid-cols-5">
		<Card />
		<Card />
		<Card />
		<Card />
		<Card />
	</div>
	<h3 class="p-2 h3">Acoustic</h3>
	<!-- Card Container -->
	<div class="grid sm:grid-cols-2 p-2 gap-2 lg:grid-cols-3 xl:grid-cols-5">
		<Card />
		<Card />
		<Card />
		<Card />
		<Card />
	</div>


</div>
			