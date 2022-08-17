<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>OK, so stay in that mindset - that what you do is right or wrong primarily because of what it means about who you are, or if not that because of the direction it's likely to make you develop in.</p> 

<p>Now Imagine you are at a party, and James, a gross person, is asking you why the host didn't invite him to the party and he had to find out about it by seeing a bouncy castle as he drove by in his smelly, terrible car. James is the worst. Everyone knows it. You know it, the host knows it, the flies know it.
</p>
<p>Regardless of what you do and don't tell him, what criteria are driving how you make that decision?
</p>

<Exits>
	<Link to=virself>I'm trying to figure out what the best version of myself would do. Like, I have a certain version of myself I hope to someday be, and I look for the action that works towards making me that person.</Link>
	<Link to=virhero>I imagine a heroically good person, real or hypothetical and then try to imagine what they'd do, and do that.</Link>
	<Link to=verminism>I try to think of what would be best for James - to nurture him, to help him to grow, and to get him to bathe.</Link>
	<Link to=panopticon>I'm honestly more worried about who I am in the sense of how other people see me. I don't care if <i>I</i> think I'm the person I should be; I care if other people do.</Link>
</Exits>
