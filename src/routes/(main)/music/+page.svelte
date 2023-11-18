<script>
import { InputChip, RangeSlider } from '@skeletonlabs/skeleton';
import MusicList from '../../../lib/components/MusicList.svelte';
import { song } from "$lib/data.js"
</script>
<div id="container" class="p-2">
  <h1 class="h2 my-1">Your Music</h1>
  <InputChip placeholder="Search your library"/>
<br>
{#each song as s}
<MusicList {...s}/>
{/each}

</div>