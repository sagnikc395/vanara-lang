<script>
	// Any interactivity or state logic goes here if needed
	import { Input } from '$lib/components/ui/input/index';
</script>

<svelte:head>
	<title>Vanara - A New Programming Language</title>
	<meta
		name="description"
		content="Vanara is a new minimalist programming language for the modern era."
	/>
</svelte:head>

<div class="flex min-h-screen flex-col justify-between bg-gray-900 text-gray-100">
	<!-- Navigation -->
	<header class="flex items-center justify-between p-6">
		<h1 class="text-2xl font-bold tracking-tight">Vanara</h1>
		<nav class="space-x-6">
			<a href="#features" class="hover:underline">Features</a>
			<a href="#docs" class="hover:underline">Docs</a>
			<a href="#github" class="hover:underline">GitHub</a>
		</nav>
	</header>

	<!-- Hero Section -->
	<main class="flex flex-1 flex-col items-center justify-center px-4 text-center">
		<h2 class="mb-4 text-4xl font-extrabold md:text-6xl">
			bringing the fun in functional programming
		</h2>
		<p class="mb-8 max-w-2xl text-lg md:text-xl">
			Vanara is a dynamically typed, fun programming language , that brings the fun back in
			functional programming.
		</p>
		<a
			href="#docs"
			class="rounded-xl bg-blue-600 px-6 py-3 font-medium transition-all hover:bg-blue-700"
		>
			Get Started
		</a>
		<h2 class="flex flex-col items-center py-4">Get notified when we release the project!</h2>
		<div class="flex w-full max-w-sm flex-col gap-1.5 py-4">
			<Input type="email" id="email" placeholder="email" />
		</div>
	</main>

	<!-- Footer -->
	<footer class="p-6 text-center text-sm text-gray-500">
		© 2025 Vanara. Built with ❤️ and pure functions.
	</footer>
</div>

<style>
	/* You can extend Tailwind with custom animations or fonts here if needed */
</style>
