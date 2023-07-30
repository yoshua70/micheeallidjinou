<script>
	import DarkmodeToggle from '../components/DarkmodeToggle.svelte';
</script>

<nav
	class="flex flex-col sm:flex-row justify-between items-center sm:items- gap-4 p-6 font-mono bg-slate-100 dark:bg-slate-950"
>
	<p>Michée Allidjinou</p>
	<div class="flex justify-evenly gap-4">
		<a href="/">Home</a>
		<a href="/blog">Blog</a>
		<a href="/projects">Projects</a>
		<a href="/about">About</a>
	</div>
	<DarkmodeToggle />
</nav>
