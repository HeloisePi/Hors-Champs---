<script>
	import Footer from './Componante/Footer.svelte';
	import Header from './Componante/Header.svelte';
	import './styles.css';
</script>

<div class="app">
	<Header />
	<main>
		<slot />
	</main>

	<footer> 
		<Footer />
	</footer>
</div>

<style>
</style>
