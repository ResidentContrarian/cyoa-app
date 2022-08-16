<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are a Risk-Averse Consequentialist.</h2>

<p>You think that it's basically OK to lie, or at least not definitionally bad. When you have the strong expectation that your lies will produce good, you do it. No worries. There's only one problem: You are skittish like a tiny baby bunny.
</p>
<p>If you were a cold, cool calculation machine, you'd be comfortable lying or not lying at even good/bad odds based on personal preference alone. But something is holding you back - either you think that people illogically don't like people trying to deceive them and might unfairly villianize you for your well-meaning trickery, or you have some cultural aversion to lying sticking to your brain like a faux-righteous stain, or something.  
</p>
<p>The point is that I'm going to need you to toughen up, my friend. When you break some eggs, you can't run away just because <i>omelettes are happening.</i>
</p>
<p>Your funny coded category name is GETSOMETHICKERSKINYOUCOWARD.
</p>


<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://residentcontrarian.com>I want to hear your post-writing-this thoughts! Back to the blog!</a>
