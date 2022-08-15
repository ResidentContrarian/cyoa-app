<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are a Life-and-Limb Anti-Lying Conditionalist.</h2>

<p>You basically think lying is absolutely wrong, except you have some semantics-based exceptions for what "lying" is. Luckily, it's only one exception, and it mostly makes sense that you'd choose the one you did. This is a pretty easy way to resolve the whole "I'd lie, and lying is bad, but this isn't somehow" paradox. If someone would be seriously endangered by you not lying, you do it. The last metroid is in captivity. The galaxy is at peace.
</p>
<p>This doesn't really tell us anything about whether or not you lie in <i>practice,</i> though. In some other branches we dig into that a little more, but here we will just note that perceptions of morality don't always align with moral practice and leave it at that.
</p>
<p>Your funny coded category name is LILIANCO.
</p>

<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://residentcontrarian.com>I want to hear your post-writing-this thoughts! Back to the blog!</a>