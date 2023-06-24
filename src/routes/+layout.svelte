<script>
	import TopNavigation from '$lib/styles/components/TopNavigation.svelte';
	import '$lib/styles/main.scss';
</script>

<main>
	<TopNavigation />
	<div class="content">
		<slot />
	</div>
</main>

<style>
	.content {
		margin-top: 64px;
	}
</style>
