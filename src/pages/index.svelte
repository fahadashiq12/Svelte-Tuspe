<script>
	let images = [
		{
			title: "Kotisivut<br>yritykselle",
			desc: "Ei vain ulkoisesti kaunis ratkaisu vaan toimiva kokonaisuus, joka myy.",
			url: "/kotisivut-yritykselle",
			img: "websites",
			alt: "Mitä kaikkea hyvin myyvät kotisivut pitävät sisällään?"
		}, {
			title: "Verkkokauppa<br>yritykselle",
			desc: "Aloita maailmanvalloitus monipuolisella ja ketterällä verkkokaupalla.",
			url: "/verkkokauppa-yritykselle",
			img: "webstores",
			alt: "Tehosta myyntiä paremmalla verkkokaupalla"
		}, {
			title: "Luotettava koti<br>verkkosivustolle",
			desc: "Meillä on turvallista ja hyvä olla. Jos sivustosi saisi valita, asuisivat ne Tuspen hoidossa.",
			url: "/yllapito",
			img: "hosting",
			alt: "Varauskalenteri Ratsukko säästää aikaa, vaivaa ja rahaa!"
		}
	]
</script>

<svelte:head>
	<style>
	@font-face {
		font-family: Montserrat;
		src: local('Montserrat ExtraBold'), local('Montserrat-ExtraBold'),
		url('/fonts/Montserrat-ExtraBold.woff2') format('woff2'),
		url('/fonts/Montserrat-ExtraBold.woff') format('woff');
		font-weight: 800;
		font-style: normal;
		font-display: swap
	}
	body,
	h3 {
		font: 400 16px Montserrat
	}
	h1,
	h2 { font-family: Montserrat; font-weight: 800 }
	#home h2 { margin-bottom: 1rem }
	#home .title {
		font-size: clamp(1.6rem, 2.6rem, 7vw);
		line-height: 1.2
	}
	#home figcaption h2 {
		font-size: 20px;
	}
	#services img { border-radius: 20px }
	#contactMe p {
		font-size: 1.2rem;
		line-height: 1.3
	}
	@media screen and (min-width:1200px){
		#services a { transition: all .6s cubic-bezier(0.165, 0.84, 0.44, 1) }
		#services a:hover img { box-shadow: 0 5px 15px rgba(0 0 0 / 30%) }
		#services a:hover figcaption h2 { color: #298fd6 }
		#services a:hover {
			transform: scale(1.1, 1.1);
			z-index: 80
		}
	}
	@media screen and (min-width:1000px){
		#home figcaption {
			top: -1.5rem;
			left: -1.2rem;
			width: 280px
		}
		#services { grid-gap: 2rem }
	}
	@media screen and (min-width:1000px){
		#home figcaption {
			position: absolute;
			background-color: #fff;
			box-shadow: 2px 2px 5px 0 rgba(0 0 0 / 30%);
			border-radius: 10px;
			padding: 1.5rem
		}
	}
	@media screen and (min-width:765px) and (max-width:1000px){
		#services { grid-gap: 1.5rem }
		#home figcaption { padding: 1.5rem 0 }
	}
	@media screen and (min-width:765px){
		#services {
			grid-template-columns: 1fr 1fr 1fr
		}
	}
	@media screen and (max-width:765px){
		.service + .service { margin-top:2rem }
		#home { padding-top: 3rem }
	}
	@media screen and (max-width:765px) and (min-width:551px){
		#home figcaption {
			bottom: -1.5rem;
			left: -1.5rem
		}
	}
	@media screen and (max-width:550px) and (min-width:350px){
		#home figcaption {
			top: -1.5rem;
			right: -1.5rem
		}
	}
	@media screen and (min-width:350px) and (max-width:765px){
		#home figcaption {
			position: absolute;
			background-color: #fff;
			box-shadow: 2px 2px 5px 0 rgba(0 0 0 / 30%);
			border-radius: 10px;
			padding: 1.5rem;
			width: 250px
		}
	}
	@media screen and (max-width:350px){
		#home figcaption { padding: 1.5rem 0 }
	}
	</style>
</svelte:head>

<div id="home">

<div class="container mxa small tc p3">
	<h1 class="title mont">Miksi tyytyä hyvään,<br>kun voi saada <a class="blue" href="/kotisivut-yritykselle">parasta</a>?</h1>
</div>

<div id="services" class="grid container mxa wide tc">
	{#each images as item}
	<a class="service tc" href={item.url} title={item.title}>
		<figure class="rel">
			<picture>
				<source srcset={"/images/"+ item.img +".webp"} media="(max-width:550px)" type="image/webp">
				<source srcset={"/images/"+ item.img +"-700.webp"} media="(max-width:500px) and (min-width:765px)" type="image/webp">
				<source srcset={"/images/"+ item.img +".webp"} media="(min-width:765px)" type="image/webp">
				<source srcset={"/images/"+ item.img +".jpg"} media="(max-width:550px)" type="image/jpeg">
				<source srcset={"/images/"+ item.img +"-700.jpg"} media="(max-width:764px)" type="image/jpeg">
				<source srcset={"/images/"+ item.img +".jpg"} media="(min-width:765px)" type="image/jpeg">
				<img src={"/images/"+ item.img +".jpg"} alt={item.alt}>
			</picture>
			<figcaption class="bgw">
				<h2 class="sub3 mont">{@html item.title}</h2>
				<p>{item.desc}</p>
			</figcaption>
		</figure>
	</a>
	{/each}
</div>

<div id="contactMe" class="container mxa small tc p3">
	<h2 class="title mont"><span class="blue">Laadukkaat verkkosivut</span><br>ovat hyvää asiakaspalvelua</h2>
	<p>Kehitä liiketoimintaasi tilaamalla uudet kotisivut yrityksellesi tai uudista nykyiset sivusi. Ota yhteyttä, saat ilmaisen kartoituksen verkkosivustosta ja ehdotuksen, miten voisimme parantaa myyntiänne.</p>
	<p><a class="btn up" href="/yhteys">Ilmainen kartoitus</a></p>
</div>

</div>