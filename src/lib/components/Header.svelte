<script>
	import Button from './Button.svelte';
</script>

<header class="fixed top-0 left-0 right-0 z-50 bg-white/90 backdrop-blur-sm border-b border-gray-100">
	<div class="mx-auto flex max-w-7xl items-center justify-between px-6 py-4">
		<!-- Logo -->
		<a href="/" class="font-display text-2xl font-semibold tracking-tight text-gray-900">
			Second Door
		</a>

		<!-- Navigation -->
		<nav class="hidden md:flex items-center space-x-8">
			<a href="#platform" class="text-sm font-medium text-gray-600 hover:text-gray-900">Platform</a>
			<a href="#pricing" class="text-sm font-medium text-gray-600 hover:text-gray-900">Pricing</a>
			<a href="#customers" class="text-sm font-medium text-gray-600 hover:text-gray-900">Customers</a>
			<a href="#resources" class="text-sm font-medium text-gray-600 hover:text-gray-900">Resources</a>
		</nav>

		<!-- Actions -->
		<div class="flex items-center space-x-4">
			<a href="#" class="text-sm font-medium text-gray-600 hover:text-gray-900">Sign In</a>
			<Button type="primary">Get Started</Button>
		</div>
	</div>
</header>
