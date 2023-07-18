<script>
	let darkMode = true;

	function toggle() {
		darkMode = !darkMode;

		darkMode
			? document.documentElement.classList.add('dark')
			: document.documentElement.classList.remove('dark');

		console.log(document.documentElement.classList);
	}
</script>

<button on:click={toggle}>
	{darkMode ? 'Go Light' : 'Go Dark'}
</button>

<style>
</style>
