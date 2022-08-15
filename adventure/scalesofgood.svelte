<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are a scales-of-good pure deontologist.</h2>

<p>You are a pure deontologist; you think rules are rules, and that breaking or obeying them is what determines the goodness of your actions. But you've found that sometimes rules conflict with each other, and when that happens things get weird for you.
</p>
<p>In this case, you've been pretty consistent that you think that lying is wrong. But you also indicated that something like "letting your neighbors get holocausted" seems <i>more wrong</i> to you, so you don't do it. On net, you come out ahead - not so good as if you weren't asked to lie at all, but not as bad as setting murders on the track of good folks. This differs a bit from consequentialism in that you still feel like you did something wrong; where they'd go "whoo! utility maximized!", you still feel bad; you sinned, just not maximally so.
</p>
<p>As with all systems where your judgment is a significant input, this can get risky. If the system providing your rules to you has a clearly defined hierarchy, that's easy. But if you are making the severity-of-sin choices yourself, you run into the risk that all flexible-sytem users do - that you eventually acclimate to the flexibility and end up a deontologist in name only. 
</p>
<p>Your funny coded category name is SCAPUDE.
</p>


<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://residentcontrarian.com>I want to hear your post-writing-this thoughts! Back to the blog!</a>
