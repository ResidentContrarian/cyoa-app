<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2></h2>

<p>OK, got it. Now, do you think that lies are wrong, right, or neutral because they mean something about who you are? That they are wrong because they in some way move you further from who you <i>should be</i>, either in the sense of "what you are supposed to become" or "becoming someone who thrives"? 
</p>



<Exits>
	<Link to=virtrack>Yeah, things are good mostly judged by the way they affect my growth.</Link>
	<Link to=contrack3>No, the effect of my lies or honesty on me isn't my major concern here.</Link>
</Exits>
