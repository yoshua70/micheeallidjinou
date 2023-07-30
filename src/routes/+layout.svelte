<script>
	import '../app.css';
	import Footer from '../components/Footer.svelte';
	import Navbar from '../components/Navbar.svelte';
</script>

<svelte:head>
	<title>Michée Allidjinou</title>
	<meta name="description" content="" />
</svelte:head>
<body class="dark:bg-slate-950 dark:text-white flex flex-col">
	<Navbar />
	<div>
		<slot />
	</div>
	<Footer />
</body>
