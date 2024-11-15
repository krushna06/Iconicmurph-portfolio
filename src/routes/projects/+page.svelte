<script lang="ts">
	import Meta from '$lib/components/Meta.svelte';
	import Project from './Project.svelte';
</script>

<Meta title="Projects – IconicMurph" description="My projects." />

<main class="wrapper fade">
	<h1 class="header">Projects</h1>

	<p class="mt-4 mb-8 text-gray-400">Some of my projects.</p>

	<Project
		name="Wace"
		href="https://wace.live"
		src="/images/projects/wace.png"
	>
		A music bot that has its own music system, premium system, playlist system, radio & Dashboard soon!
	</Project>
</main>
