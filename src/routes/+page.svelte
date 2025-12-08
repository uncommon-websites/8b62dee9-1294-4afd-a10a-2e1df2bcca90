<script lang="ts">
	import Header from "$lib/components/Header.svelte";
	import Hero from "$lib/components/Hero.svelte";
	import Partners from "$lib/components/Partners.svelte";
	import ValueProp from "$lib/components/ValueProp.svelte";
	import Carousel from "$lib/components/Carousel.svelte";
	import ClinicalIntelligence from "$lib/components/ClinicalIntelligence.svelte";
	import SeamlessExperiences from "$lib/components/SeamlessExperiences.svelte";
	import CaseStudies from "$lib/components/CaseStudies.svelte";
	import History from "$lib/components/History.svelte";
	import Newsroom from "$lib/components/Newsroom.svelte";
	import CTA from "$lib/components/CTA.svelte";
	import Footer from "$lib/components/Footer.svelte";
</script>

<div class="min-h-screen bg-white">
	<Header />
	<main>
		<Hero />
		<Partners />
		<ValueProp />
		<Carousel />
		<ClinicalIntelligence />
		<SeamlessExperiences />
		<CaseStudies />
		<History />
		<Newsroom />
		<CTA />
	</main>
	<Footer />
</div>

