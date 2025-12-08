<script>
	import Button from './Button.svelte';
</script>

<header class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm">
	<div class="mx-auto flex max-w-7xl items-center justify-between px-6 py-4">
		<!-- Logo -->
		<a href="/" class="font-display text-3xl font-medium tracking-tight text-gray-900">
			fabric
		</a>

		<!-- Navigation -->
		<nav class="hidden md:flex items-center space-x-8">
			<a href="#platform" class="text-sm font-medium text-gray-600 hover:text-gray-900">Platform & Services</a>
			<a href="#solutions" class="text-sm font-medium text-gray-600 hover:text-gray-900">Solutions</a>
			<a href="#resources" class="text-sm font-medium text-gray-600 hover:text-gray-900">Resources</a>
		</nav>

		<!-- Actions -->
		<div class="flex items-center space-x-4">
			<button class="text-gray-500 hover:text-gray-900">
				<svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><circle cx="11" cy="11" r="8"/><path d="m21 21-4.3-4.3"/></svg>
			</button>
			<Button type="primary">Request a demo</Button>
		</div>
	</div>
</header>
