<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>So you have this theoretical or actual role model who, basically, you trust to do things correctly; you look to what they do and imitate them. Got it. But the next relevant thing seems to be asking this: What kind of person are they? 
</p>
<p>In this case, we could make arguments in favor of lying by saying "My role model would probably err towards honesty here for the sake of being a reliable person.". Or "My role model would seek to peacekeep", or even "My role model tends to avoid hard truths at all costs because X" where X is any reasoning that thinks that James should figure out about soap on his own time.
</p>
<p>What's the preference here?
</p>
<p>(Full disclosure: It doesn't matter that you picked an actual or theoretical third party here; it leads to the same options as if you didn't. I just wanted you to think about it.)
</p>

<Exits>
	<Link to=virneverlie>They NEVER lie. They are a perfect person.</Link>
	<Link to=virseldomlie>They RARELY lie. They are a perfect person who adjusts his actions to suit the situation, but he has a strong bias towards truth.</Link>
	<Link to=viroftenlie>They OFTEN lie. They are a perfect person who considers things situationally, and acts mostly in accordance to what they think will produce great outcomes</Link>
</Exits>