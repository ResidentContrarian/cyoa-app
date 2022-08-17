<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>OK, thanks for bearing with me. We are now properly and fully on the consequentialist track.
</p>
<p>You've indicated that you don't think lies are bad because lies themselves are inherently bad, which pretty much knocks out all forms of deontology. You've also indicated that you don't think that lies are bad because of the kind of person they imply you are or make you into, which mostly knocks out virtue ethics. In terms of big, comprehensible moral structures, that pretty much leaves us with consequentialism. Which is tough on me, because there's far more branches to consequentialism than any other way we could go here.
</p>
<p>So first: Consequentialism thinks that actions are wrong or right based on their consequences. Can you, through some kind of predictive power, know what the future consequences of any given action are 100% of the the time, or close to it?
</p>


<Exits>
	<Link to=conpsychic>Pretty much, yes. I'm really, really good at knowing what's coming.</Link>
	<Link to=conuncertain>No, I can't. I don't think anybody can really predict things that well.</Link>
</Exits>
