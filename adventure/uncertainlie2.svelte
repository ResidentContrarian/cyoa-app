<script>
	import Action from './helpers/Action.svelte'
	import Blue from './helpers/Blue.svelte'
	import Exits from './helpers/Exits.svelte'

	export let Link, state


</script>

<p>One last thing: The preferences and opinions of of those you are lying to.
</p>
<p>You are working in a system of uncertainty. People disagree on things in uncertain systems, and one such disagreement you might run into is a a person who believes his utility is severely diminished by you lying to him. For instance, he may ask if a food contains a certain ingredient you think is harmless but he thinks is harmful. It might be something with lower or higher stakes than that.
</p>
<p>In instances where the person has made it clear they don't think they'd get net utility from you lying to them (and where no other factors but your and their utility is considered), do you consider your thought-out utility calculation to be more valid than theirs in a way that often would lead you to lie anyway?
</p>

<Exits>
	<Link to=thegenius>I didn't make the calculation based on nothing, man. The calculation <i>is</i> my decision.</Link>
	<Link to=thedeferential>No, I'd respect their wishes.</Link>
</Exits>