<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2></h2>

<p>OK, you've indicated that you are going to lie to the Nazi here; that's definitely not all downsides, since your neighbors live. But why did you lie? 
</p>

<Exits>
	<Link to=detractconfork>At some point, the consequences outweigh the rightness or wrongness of the action. In this case, people were going to die; I think my action wasn't wrong considering that.</Link>
	<Link to=scalesofgood>The action of lying is wrong, and no amount of consequences can nullify that. But lying here seems like it would break some higher-order rules; I think "thou shalt not lie" just got outranked here.</Link>
	<Link to=detracksometimesyousin>Actually, it's neither. I think that lying is morally wrong in this case, I just couldn't face the music of living up to my moral ideals.</Link>
</Exits>
