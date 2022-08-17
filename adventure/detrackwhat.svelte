<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>Really? This is a nice family. Let's say Nazis are the abstract-concept version of Nazis; there's no reasoning behind what they are doing, no justifications at all besides doing bad things to good people. Is it still wrong to lie to save them?
</p>

<Exits>
	<Link to=detrackwhynot>Oops! No, that was a misclick.</Link>
	<Link to=detrackwhat2>Yes, I meant what I said.</Link>
</Exits>
