<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>
	Do you think that lying is wrong in an absolute sense? I'm not saying "it's wrong because it always works out to be a net negative, and net negatives are wrong"; Do you think it's wrong to lie, even when the consequences would be positive? That's it's wrong in an abstract sense unaffected by circumstance or consequence? As if it's baked into the definitions of the universe or deemed that way by an ultimate authority of some kind?
</p>

<Exits>
	<Link to=contrack>No, I don't think morality works off an abstract list like that.</Link>
	<Link to=detrack>Yes, that's how morality works; some wrong things carry their wrongness with them.</Link>
</Exits>
