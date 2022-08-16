<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>We are now mostly on the consequentialist track, but there's just a little more weirdness to sort through:
</p>
<p>Do you priviledge yourself and your desires/benefit above others when choosing to lie or not lie? Now, I don't mean just a bit - I think everyone probably does just a bit. I'm talking more about a very significant bias towards yourself that shows itself whenever you choose to lie. So if James-The-Unwashed-Killer-of-Vibe was asking you why he didn't get invited to the party, you might or might not priveledge yourself (in avoiding the awkwardness of telling him, or in telling him and getting to bask in his sorrow) over things like the greater, society-wide consequences.
</p>
<p>Again, everyone does this kind of stuff a little; it's very, very hard not to. I'm more asking if it's the primary driver of the decision in a way that usually predicts your eventual action.
</p>


<Exits>
	<Link to=contrack4>No; I either don't consider my own wants at all or don't treat them as my primary decision criteria when lying.</Link>
	<Link to=cartman>Yes; if you looked at a spreadsheet of my lies, the majority of them would line up exactly with what I wanted to do anyway.</Link>
</Exits>
