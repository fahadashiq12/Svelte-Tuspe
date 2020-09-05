<script>
	import { metatags } from "@sveltech/routify"
	let title = "Helppokäyttöinen urheilusaitti seuralle"
	let desc = "Kotisivut ovat pelivälineesi digikentällä. Hyvin rakennetut ja toimivat sivut ovat ilo silmälle, aperitiivi ostohalulle sekä tehty maali asiakkaan bisnekseen."
	let url = "https://tuspe.com/sportti"
	metatags.title = title +" | Tuspe Design"
	metatags.description = desc
	metatags.url = url
	metatags.canonical = url
	metatags["twitter:card"] = "summary_large_image"
	metatags["twitter:title"] = title
	metatags["twitter:description"] = desc
	let sites = [
		{
			title: "Joensuun Kiekko-Pojat",
			url: "https://joensuunkiekkopojat.fi/",
			img: "jokipo"
		}, {
			title: "Kiekko-Vantaa",
			url: "https://kiekko-vantaa.fi/",
			img: "kiekkovantaa"
		}, {
			title: "Kurra",
			url: "https://www.kurra.fi/",
			img: "kurra"
		}, {
			title: "Käpylän Pallo",
			url: "https://kapylanpallo.fi/",
			img: "kapa"
		}, {
			title: "Pallokerho Keski-Uusimaa",
			url: "https://pkku.fi/",
			img: "pkku"
		}, {
			title: "RoKi Hockey",
			url: "https://rokihockey.fi/",
			img: "roki"
		}
	]
</script>

<svelte:head>
	<link rel="stylesheet" href="/page.css">
	<style>
		a.logo {
			width: 120px;
			height: 120px;
			padding: 10px
		}
	</style>
</svelte:head>

<div id="page">

<section id="about">
	<div class="img left">
		<picture>
			<source srcset="/images/sport-page-mobile.webp" media="(max-width:999px)" type="image/webp">
			<source srcset="/images/sport-page.webp" media="(min-width:1000px)" type="image/webp">
			<source srcset="/images/sport-page-mobile.jpg" media="(max-width:999px)" type="image/jpeg">
			<source srcset="/images/sport-page.jpg" media="(min-width:1000px)" type="image/jpeg">
			<img src="/images/sport-page.jpg" alt={title}>
		</picture>
	</div>
	<div class="txt cell mxa">
		<div class="content">
			<h1 class="w3">Monipuolinen ja helposti päivitettävä urheilusaitti</h1>
			<p>Elämän ei pidä olla vaikeaa, kallista ja aikaa vievää seuran kotisivuja päivittäessä. Mitäs jos hoitaisimme kaikki matsit joukkuettain automaattisesti ja päivittäisimme vielä tuloksetkin pelien jälkeen? Videot? Tilastot? Check. Haluamme säästää sinun aikaasi tärkeämmälle.</p>
			<p>Olemme kehittäneet urheilusaittimme vastaamaan seurojen tarpeita ja kehitämme sitä koko ajan paremmaksi Mestis-seurojemme avulla. Haluamme, että seurojen fanit saavat erittäin hyvän kokemuksen vierailusta sekä seurojen on helppoa päivittää ja lisätä sisältöä. Ominaisuuksia on automatisoitu niin pitkälle kuin mahdollista.</p>
			<p>Urheilusaittimme perusominaisuuksiin kuuluvat mm. helposti luotavat uutiset, komeat pelaajaesittelyt, videot YouTubesta, tilastot ja ottelut Tilastokeskukselta, verkko- ja huutokauppa, aitioden esittelyt ja varaukset, kausipaikat sekä paljon muuta seuran elämää helpottavia ominaisuuksia.</p>
			<p><a class="btn up" href="/yhteys">Nyt palloa maaliin!</a></p>
		</div>
	</div>
</section>

<section class="p3">
	<div class="container mxa small tc"><h2 class="w3 sub1">Liitetäänkö sinunkin seurasi huippujoukkoon?</h2></div>
	<div class="container mxa wide tc">
		<div id="logos">
		{#each sites as item}
			<a class="logo inl" href={item.url} target="_blank">
				<picture>
					<source srcset={"/images/logos/"+ item.img +".webp"} type="image/webp">
					<source srcset={"/images/logos/"+ item.img +".png"} type="image/png">
					<img src={"/images/logos/"+ item.img +".png"} alt={item.title} width="100" height="100">
				</picture>
			</a>
		{/each}
		</div>
	</div>
</section>

</div>