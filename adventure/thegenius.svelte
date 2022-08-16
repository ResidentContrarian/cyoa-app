<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are a Logical Consequentialist Dictator.</h2>

<p>You are a pretty stock interpretation of a Wikipedia-level understanding of consequentialism - I know, because that's the level I understand consequentialism at and this is about what I expected from you.
</p>
<p>You will lie any time it seems like there will probably be a net benefit from doing so. You will also, as a bonus, lie to someone who is very clear in telling you they don't want that. This is convenient, since most people don't like being lied to. You are pretty sure you are smarter than them, even to the point where your second-party information disadvantage mitigates their first-party knowledge of their own situation. You also don't put weight on their preference and desires, or at least not enough to keep you from doing what you decided was right anyway.
</p>
<p>Your funny coded category name is THEGENIUS.
</p>


<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://residentcontrarian.com>I want to hear your post-writing-this thoughts! Back to the blog!</a>
