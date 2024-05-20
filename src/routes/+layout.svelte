<script>
	import '../app.css';
	import Footer from '../components/Footer.svelte';
	import Navbar from '../components/Navbar.svelte';
</script>

<main class="overflow-x-hidden">
	<Navbar />
	<slot />
	<Footer/>
</main>
