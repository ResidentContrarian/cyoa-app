<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2></h2>

<p>Really? This is a nice family. Let's say Nazis are the abstract-concept version of Nazis; there's no reasoning behind what they are doing, no justifications at all besides doing bad things to good people. Is it still wrong to lie to save them?
</p>

<Exits>
	<Link to=detrackwhynot>Oops, no, misclick.</Link>
	<Link to=detrackwhat2>Yes, Still.</Link>
</Exits>
