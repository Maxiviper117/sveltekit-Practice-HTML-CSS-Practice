<script lang="ts">
	//

	import DesktopDesign from '$lib/components/desktop-design.svelte';
	import DesktopSucess from '$lib/components/desktop-sucess.svelte';
</script>

<!-- <div class="header">
	<h1>Welcome to SvelteKit</h1>
	<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
</div> -->

<div class="container">
	<DesktopSucess />
	<DesktopDesign />
</div>

<style lang="scss">
	.header {
		background-color: #f0f0f0;
	}

	.container {
		display: flex;
		flex-direction: column;
		padding: 2rem 0;
		gap: 2rem;
	}
</style>
