<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";
</script>

<CustomerCardHero
	title="Accelerate your cash flow by 15 days"
	subtitle="Core Ranger automates billback processing to eliminate manual invoice reconciliation and deliver payments faster than ever."
	centered={true}
	customers={[
		{
			name: "Sarah Martinez",
			position: "Finance Director",
			imageSrc: "/generated/image-a-professional-female-finance-director-s.webp"
		},
		{
			name: "Michael Chen",
			position: "Finance Manager", 
			imageSrc: "/generated/image-a-professional-male-finance-manager-in-a.webp"
		},
		{
			name: "Lisa Thompson",
			position: "Operations Director",
			imageSrc: "/generated/image-a-professional-female-operations-directo.webp"
		},
		{
			name: "David Rodriguez",
			position: "CFO",
			imageSrc: "/generated/image-a-professional-male-cfo-stands-in-a-mode.webp"
		},
		{
			name: "Jennifer Park",
			position: "VP Finance",
			imageSrc: "/generated/image-a-professional-female-vp-of-finance-stan.webp"
		}
	]}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/pepsi.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/coca-cola.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/anheuser-busch.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/molsoncoors.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Rebecca Martinez",
			position: "Finance Director",
			company: "Northeast Beverage Distributors",
			quote:
				"Core Ranger cut our billback processing time from 3 weeks to same day. We're now collecting $2.3 million faster each quarter, which completely transformed our cash flow management.",
			image: "/generated/image-1-a-professional-female-finance-director.webp"
		},
		{
			name: "Marcus Thompson",
			position: "CFO",
			company: "Pacific Coast Distribution",
			quote:
				"Before Core Ranger, we had two full-time employees just reconciling invoices manually. Now they focus on strategic finance work while the system handles everything automatically with 99.8% accuracy.",
			image: "/generated/image-2-a-professional-male-cfo-in-a-sharp-sui.webp"
		},
		{
			name: "Diana Chen",
			position: "VP of Operations",
			company: "Midwest Supply Partners",
			quote:
				"The risk of missing billback deadlines kept me up at night. Core Ranger's real-time error detection caught $180,000 in discrepancies we would have lost forever.",
			image: "/generated/image-3-a-professional-female-operations-vp-in.webp"
		}
	]}
/>

<Features
	title="Automated billback processing that transforms cash flow"
	subtitle="Purpose-built for distributors who need to capture every dollar and accelerate payments"
	features={[
		{
			title: "Day 1 billback processing",
			description: "Process billbacks immediately instead of waiting for mid-month cycles. Accelerate your cash flow by 15 days through real-time automation that eliminates manual invoice reconciliation.",
			imageSrc: "/generated/image-1-early-morning-in-a-real-distribution-c.webp"
		},
		{
			title: "Real-time error detection",
			description: "Catch discrepancies instantly with comprehensive rules and matching systems. Never lose revenue to manual oversights or delayed claim processing.",
			imageSrc: "/generated/image-2-wide-angle-shot-of-a-professional-ware.webp"
		},
		{
			title: "Zero workflow disruption",
			description: "Same-day implementation with guaranteed zero disruption to your existing processes. Start processing billbacks faster without changing how your team works.",
			imageSrc: "/generated/image-3-small-group-of-business-professionals-.webp"
		},
		{
			title: "Comprehensive claims matching",
			description: "Capture every dollar through intelligent automation that processes complex supplier billbacks with precision.",
		},
		{
			title: "Eliminates manual processes",
			description: "Replace spreadsheets, email chains, and supplier portals with one automated system that handles everything.",
		},
		{
			title: "Built for distribution scale",
			description: "Proven to handle $1.8+ billion in annual processing volume across 40+ million cases with enterprise reliability.",
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
