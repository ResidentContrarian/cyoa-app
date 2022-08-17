<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>Your are an Omniscient Consequentalist Paternalist.</h2>

<p>You care about consequences, and only consequences. You know all outcomes, and only all outcomes. Where people say they prefer to know the truth, consequences be damned, you know better and enforce your will upon them lest they lead themselves astray.
</p>
<p>There's a few different end-states in this project that I basically suspect don't exist in real life; this is one, for reasons you probably find clear. But I feel like this is also a situation which would come up in thought problems, since the level to which you can predict outcomes is pretty important to how viable consequentialism is as a moral system. 
</p>
<p>There's other endings where the liar is disregarding the wishes of the lied to, but for the record I like this one more than most of them; at least here the person is pretty certain they are maximizing utility, even if they might be mistaken.
</p>
<p>Your funny coded category name is PAPAOMNICON.
</p>


<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://www.residentcontrarian.com/p/post-interactive-nonfiction-thoughts>I want to hear your post-writing-this thoughts! Back to the blog!</a>
