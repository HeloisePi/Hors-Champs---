<script>
	import Hero from "./Componante/Hero.svelte";
	import Video from "./Componante/Video.svelte";
	import Person from "./Componante/Person.svelte";
	import InpirationColo from "./Componante/InpirationColo.svelte";
	import InspirationGenre from "./Componante/InspirationGenre.svelte";
	import Remerciment from "./Componante/Remerciment.svelte";

</script>

<svelte:head>
	<title>À la recherche du chat </title>
	<meta name="Cours-Métrage - Hors CHAMPS" content="Description des différents éléments de la production du court-métrage" />
</svelte:head>

<section class="all">
	<Hero/>
	<Video 
	title="COURT MÉTRAGE"
	videoSrc="#" />
	<div class="">
		<h2>CRÉDITS</h2>
		<div class="creditPerson" id="credit">
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
	</div>

	<InpirationColo />
	<InspirationGenre />
	<Video 
	title="Making Of"
	videoSrc="#" />
	<Remerciment />
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

	.all{
		display: flex;
		flex-direction: column;
		gap: 10rem;
	}
</style>
