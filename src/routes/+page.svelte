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
				srcImg="/images/portrait/hugo.webp"
				name ="Hugo"
				description ="Acteur, Motion designer, Scénariste"
			/>
			<Person 
				srcImg="/images/portrait/jo.webp"
				name ="jo"
				description ="Actrice, Monteuse, Scénariste"
			/>
			<Person 
				srcImg="/images/portrait/astrid.webp"
				name ="astrid"
				description ="Monteuse, metteur en scène, Scénariste"
			/>
			<Person 
				srcImg="/images/portrait/heloise.webp"
				name ="héloïse"
				description ="Silhouette, Assistant réal, Scénariste, DA"
			/>
			<Person 
				srcImg="/images/portrait/chloe.webp"
				name ="chloé"
				description ="Réalisatrice, Costumière, Scénariste, Monteuse, DA"
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
	@media screen and (max-width: 970px) {
		.creditPerson{
		grid-template-columns: 1fr 1fr 1fr 1fr ;
		grid-template-rows: 1fr 1fr;
		column-gap: 1rem;
		row-gap: 1rem;
		width: 100vw;
	}
	@media screen and (max-width: 970px) {
		.creditPerson{
			grid-template-columns:  1fr 1fr ;
		}
	}
	@media screen and (max-width: 400px) {
		.creditPerson{
			grid-template-columns:  1fr ;
		}
	}

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
