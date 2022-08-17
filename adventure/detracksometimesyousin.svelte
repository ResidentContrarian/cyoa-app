<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<h2>You are an Imperfect Anti-Lying Absolutist.</h2>

<p>You think the action of lying is wrong, full-stop. The consequences of a lie (or of telling the truth) aren't included in the formula you use to calculate the rightness of the action. Somewhere in your universe, there's a stone slab with "lying is always wrong" carved into it, and you think the slab is right.
</p>
<p>With that said, you admit you will actually take the sin-hit and lie in at least some circumstances - for instance, when someone's life is at stake. You might (or might not!) actually lie kind of a lot, but that's an admission you are making about your own imperfection.
</p>
<p>It's worthwhile to note that you are different from someone who has exceptions they believe remove the wrongness from the lie; that exists in a couple different forms in this game, but you aren't it. Bear in mind I'm not judging at all here; "I think lying is always wrong, but I do it sometimes anyway because I'm not perfect" is about the strongest claim a person can make about lying that I easily believe.
</p>
<p>Your funny coded category name is IMANLABS.
</p>


<Exits>
	<Link to=Start>I want to try again! Back to the top!</Link>
</Exits>
<a href=https://www.residentcontrarian.com/p/post-interactive-nonfiction-thoughts>I want to hear your post-writing-this thoughts! Back to the blog!</a>
