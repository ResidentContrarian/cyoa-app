<script context=module>
	import initial_state from './initial_state.js'

	export {
		initial_state,
	}
</script>

<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state

</script>

<h2>What is Lying?</h2>

	<p>
		I'm interested in concepts related honesty and lies. If you are here, you probably are too, even if only a bit. 
	</p>
	<p>
		This is an exercise in defining a conceptual space. I want to give people an opportunity to sort of walk through the exact thoughts they have on lying - what makes it right, what makes it wrong, when they do it - as opposed to actually telling them what I think about it. 
	</p>
	<p>
		I'm going to try to keep judgment from leaking through too much, but I'm sure it will some places. Feel free to mentally eat around that particular patch of mold; again, I'm trying to make a tool for defining your own views on honesty, not mine.
	</p>
	<p>
		With all that said, let's get going!
	</p>

	<Exits>
		<Link to=Absolutes>Let's go!</Link>
	</Exits>