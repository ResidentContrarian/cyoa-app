<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2></h2>

<p>So the belief that lying is always wrong - wrong at an act-level, as opposed to wrong at a consequences-level, is a pretty strong stance. Is that stance conditional?
</p>
<p>
	Like, assume (as we often must) a Nazi Germany situation. You know the location of a Jewish family, and a Nazi asks you where they are so he can go round them up and ship them to near-certain doom. Is it still wrong to lie?
</p>
<p>
	Note that what I'm trying to get at here is the situation that justifies lying the most. If you can think of one that does that better, sub it in.
</p>
<p>
</p>
<p>
</p>

<Exits>
	<Link to=detrackwhat>Yes.</Link>
	<Link to=detrackwhynot>Well, no, not then, obviously.</Link>
</Exits>
