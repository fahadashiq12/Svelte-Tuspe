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
	<link rel="stylesheet" href="/home.css"> 
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