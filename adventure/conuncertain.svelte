<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>To be very clear, you've chosen wisely here. The guys who are claiming they know the outcomes in advance? They aren't even full of shit. They are just clicking that link to see how I handle it. I'm going to reward you by saving you time and just telling you: I handled it <i>poorly.</i> Turns out this choose-your-own-adventure stuff is a lot of work.
</p>
<p>OK, so, given that you aren't sure of the consequences, does that uncertainty stop you from lying? Like, say you've got <75% certainty the lie is going to be net-good. Do you still lie?
</p>


<Exits>
	<Link to=nouncertainlie>No, I only lie when I'm pretty damn sure it's going to cause some good.</Link>
	<Link to=uncertainlie>This is still a net positive for our great city. I'm lying here.</Link>
</Exits>
