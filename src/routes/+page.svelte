<script>
	import Hero from "./Componante/Hero.svelte";
	import Video from "./Componante/Video.svelte";
	import Person from "./Componante/Person.svelte";

</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
</svelte:head>

<section>
	<Hero/>
	<Video 
	title="COURT MÉTRAGE"
	videoSrc="#" />
	<h2>CRÉDITS</h2>
	<div class="creditPerson">
		<Person 
			srcImg="src/assets/images/portrait/hugo.png"
			name ="Hugo"
			description ="Lorem ipsum dolor sit, amet consectetur"
		/>
		<Person 
			srcImg="src/assets/images/portrait/jo.png"
			name ="jo"
			description ="Lorem ipsum dolor sit, amet consectetur"
		/>
		<Person 
			srcImg="src/assets/images/portrait/astrid.png"
			name ="astrid"
			description ="Lorem ipsum dolor sit, amet consectetur"
		/>
		<Person 
			srcImg="src/assets/images/portrait/heloise.png"
			name ="héloïse"
			description ="Lorem ipsum dolor sit, amet consectetur"
		/>
		<Person 
			srcImg="src/assets/images/portrait/chloe.png"
			name ="chloé"
			description ="Lorem ipsum dolor sit, amet consectetur"
		/>
	</div>
</section>

<style>
	.creditPerson{
		display: grid;
		grid-template-columns: 1fr 1fr 1fr 1fr 1fr;
		column-gap: 1rem;
		width: 100vw;
		padding-left: 10vw;
		padding-right: 10vw;
	}
	h2{
		padding-left: 10vw;
		padding-bottom: 1rem;
	}
</style>
