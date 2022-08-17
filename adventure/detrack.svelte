<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>


<p>So the belief that lying is abstractly wrong - wrong at an act-level, as opposed to wrong at a consequences-level, is a pretty strong stance. Is that stance at all conditional?
</p>
<p>
	Like, assume (as we often must) a Nazi Germany situation. You know the location of a Jewish family, and a Nazi asks you where they are so he can go round them up and ship them to near-certain doom. If you tell the complete truth, they die; if you lie about where they've gone, he won't find them and will just assume they got away. If you truthfully say you know where they are but refuse to tell, they will torture the information out of you and then kill you. Is it still wrong to lie?
</p>
<p>
	Note that what I'm trying to get at here is the situation that justifies lying the most. If you can think of one that does that better, sub it in. You have full permission to create scenarios where not lying immediately causes the heat death of the universe or whatever floats your boat here.
</p>

<Exits>
	<Link to=detrackwhat>Yes, I'd tell the Nazi where to find them.</Link>
	<Link to=detrackwhynot>Well, no. I'd lie then, obviously.</Link>
</Exits>
