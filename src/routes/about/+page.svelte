<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Customer obsession",
			description: "Every feature we build starts with one question: how does this accelerate our customers' cash flow?"
		},
		{
			title: "Automate everything",
			description: "Manual processes drain resources and create errors. We eliminate spreadsheets, emails, and portals to let finance teams focus on strategy."
		},
		{
			title: "Speed matters",
			description: "15 days faster cash flow isn't just a metric—it's the difference between thriving and surviving in distribution."
		}
	];
</script>

<SecondaryHero
	title="Faster cash. Fewer headaches."
	subtitle="Automated billbacks for modern distributors"
	imageSrc="/generated/image-editorial-documentary-photograph-of-a-sm.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- CTA Section -->
<CallToAction
	title="Accelerate your cash flow today"
	subtitle="See results in 15 days or less"
	description="Stop losing money to manual billback processing. Join 500+ distributors who've eliminated spreadsheets and accelerated their cash flow with Core Ranger's automated solution."
	imageSrc="/generated/image-a-professional-finance-director-in-tailo.webp"
/>
