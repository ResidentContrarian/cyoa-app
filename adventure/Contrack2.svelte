<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2></h2>

<p>OK, got it. Now, do you think lying is wrong (or right) because it either <i>has a tendency to make you worse (or better!), in terms of your value as a person</i> or indicates that you <i>are worse (or better!), in terms of your value as a person, than some hypothetical perfect person who chooses not to lie?</i> That lying isn't wrong or right as such, but instead is a potentially neutral action that really, really top-notch people do or don't do?
</p>


<Exits>
	<Link to=virtrack>Yeah!</Link>
	<Link to=contrack3>No.</Link>
</Exits>
