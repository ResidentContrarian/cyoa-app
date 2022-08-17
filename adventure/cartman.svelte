<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are a Do-What-I-Want Chaos-Monster.</h2>

<p>Well, kind of. Chaos-Monster is a little strong, and a little inaccurate.
</p>
<p>The deal here is that you are mostly not concerned with lying or not lying so much as you are with making sure things turn out well for you. And I want to be really honest here: There's probably more people in your group than any of the others in this whole survey. I don't think it's <i>great</i>; neither do you when I put it in these terms. But at the same time, there's an awful lot of people in this group; it takes active work to get out of this category, and like most things that take active, extra effort most people don't end up actually doing it.
</p>
<p>What sets you apart (and makes you a little better) is that you actually are (presumably) honest about it. All the other groups - deontologists, consequentialists, virtue ethics folks - have plenty of people who have adopted a moral system only in the sense that it's their favorite one. It doesn't drive action for them. It doesn't necessarily drive action for you, either, but at least you aren't a hypocrite about it.
</p>
<p>Your funny coded category name is CARTMAN.
</p>

<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://www.residentcontrarian.com/p/post-interactive-nonfiction-thoughts>I want to hear your post-writing-this thoughts! Back to the blog!</a>

