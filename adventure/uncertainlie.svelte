<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>To save time, I'm going to assume that your answer to the last question means you would probably lie down to some threshold reasonably close to 50% certainty of net-good outcomes. And listen: I'm sure there's some complexity here I'm missing, but the superficial implication of consequentialism-takes on lying is sort of that this is the right call; if you are optimizing for outcomes, you lie when it seems like it's going to make good outcomes. Whether or not I like the system, I get that this makes sense within it.
</p>
<p>With that said, we now have to take a short intermission to eliminate one last weird outlier: Would you lie if the chances of net-good consequences directly stemming from that lie were LESS than 50%?
</p>

<Exits>
	<Link to=uncertainlie2>No, I wouldn't lie in that situation.</Link>
	<Link to=netneglie>Yes, I would lie at a less-than-50% good-consequence certainty.</Link>
</Exits>
