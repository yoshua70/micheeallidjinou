<script>
	import '../app.css';
	import Footer from '../components/Footer.svelte';
	import Navbar from '../components/Navbar.svelte';
</script>

<svelte:head>
	<title>Michée Allidjinou</title>
	<meta name="description" content="" />
</svelte:head>
<body class="dark:bg-slate-950 dark:text-white flex flex-col min-h-screen">
	<Navbar />

	<main class="flex flex-1 flex-col">
		<article class="flex flex-1 justify-center bg-white p-6 dark:bg-slate-950 dark:text-red-300">
			<slot />
		</article>
	</main>

	<Footer />
</body>
