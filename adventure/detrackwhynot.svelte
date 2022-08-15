<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>Why not? You told me lying was abstractly wrong a minute ago; what changed?
</p>

<Exits>
	<Link to=detrackmitigate>It's not exactly lying at that point.</Link>
	<Link to=detracknaziactuallylie>It's not really wrong at that point, or something like that.</Link>
</Exits>
