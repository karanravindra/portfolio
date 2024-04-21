<script>
	import '../app.pcss';
	import Navbar from '$components/navbar.svelte';
	import Footer from '$components/footer.svelte';
</script>

<main class="container mx-auto h-screen">
	<Navbar />
	<slot />
	<Footer />
</main>
