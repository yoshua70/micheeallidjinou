<script>
	import { onMount } from 'svelte';

	let darkMode = true;
	let label = 'Go Light';

	onMount(() => {
		label = document.documentElement.classList.contains('dark') ? 'Go Light' : 'Go Dark';
	});

	function toggle() {
		console.log('Before:', darkMode);
		darkMode = !darkMode;
		console.log('After', darkMode);

		darkMode
			? document.documentElement.classList.add('dark')
			: document.documentElement.classList.remove('dark');

		label = darkMode ? 'Go Light' : 'Go Dark';
	}
</script>

<button on:click={toggle}>
	{label}
</button>

<style>
</style>
