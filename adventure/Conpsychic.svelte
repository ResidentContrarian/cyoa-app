<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>You are a mentat or in some way gifted with prescience, and can thus pretty well predict what's going to happen in the future as a consequence of your lie. Because you are also a consequentialist, this means you know the moral implications of every lie to a high level of fidelity. 
</p>
<p>That seems like it should be it, since we've covered that you don't think lying is intrinsically right and that you don't just lie because you feel like it. All that's really left is lying because some level of net utility convinces you it's worth it. 
</p>
<p>Here's one last wrinkle, though. Say James has once again given you call to maybe-lie by asking why people don't like him. In your omniscience, you have determined that him knowing that it's because he doesn't bath would be net-negative to him. You don't think that it would hurt anyone else if he knew, and you yourself don't mind telling him besides the net-negative thing.
</p>
<p>James himself has been very, very clear in the past that his preference is to always hear the truth if at all possible; you know to a reasonable level of certainty he'd actually be mad later if he found out you lied to him. In this scenario, do you respect James' preference, or do you opt to do what you think will maximize his utility?
</p>

<Exits>
	<Link to=knowledgedisregard>Of course I don't - I think it's wrong to not maximize utility, we've covered this.</Link>
	<Link to=knowledgerespect>Of course I don't - you can't <i>completely</i> disregard the desires of others.</Link>
</Exits>
