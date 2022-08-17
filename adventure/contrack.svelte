<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>OK, you've reached what will be, for most people, the consequentialist track of this thing. But before we can assume that 100%, we need to eliminate some outliers. Believe me that it's much easier to do this now than later. So, first: Do you think lying is inherently right? We already ruled out the idea that lying is intrinsically wrong in a self-contained-morality-of-act way; do you think the opposite is true, and that lying is always right? That the rightness of lying is baked into lying itself?
</p>

<Exits>
	<Link to=Contrack2>What? No, of course not.</Link>
	<Link to=Antide>Yes. Consequences aside, lies are inherently good.</Link>
</Exits>
