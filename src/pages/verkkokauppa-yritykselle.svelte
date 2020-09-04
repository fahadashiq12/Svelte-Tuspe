<script>
	import { metatags } from "@sveltech/routify"
	import Hosting from "../components/Hosting.svelte"
	let title = "Suunnittelemme ja toteutamme verkkokaupan yrityksellesi"
	let desc = "Kotisivut ovat pelivälineesi digikentällä. Hyvin rakennetut ja toimivat sivut ovat ilo silmälle, aperitiivi ostohalulle sekä tehty maali asiakkaan bisnekseen."
	let img_alt = "Aloita maailman valloitus Tuspen verkkokaupalla"
	let url = "https://tuspe.com/verkkokauppa-yritykselle"
	metatags.title = title +" | Tuspe Design"
	metatags.description = desc
	metatags.url = url
	metatags.canonical = url
	metatags["twitter:card"] = "summary_large_image"
	metatags["twitter:title"] = title
	metatags["twitter:description"] = desc
	metatags["twitter:image:alt"] = img_alt
	let refs = [
		{
			title: "NavyBlue Shop",
			url: "https://navyblue.fi/",
			img: "processwire-navyblue-2020",
			tech: "ProcessWire, Lemonsoft, PHP, SQL",
			fi: {
				desc: "Tyylikkäitä ja kovissakin olosuhteissa toimivia sporttisia vaatteita, asusteita ja jalkineita.",
				img: "Tyylikkäitä ja kovia olosuhteita kestäviä sporttisia vaatteita, asusteita ja jalkineita."
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Lennol",
			url: "https://www.lennol.fi/",
			img: "processwire-lennol-2019",
			tech: "ProcessWire, Lemonsoft, PHP, SQL",
			fi: {
				desc: "Sisustustekstiiliyritys, joka tarjoaa ylellistä kauneutta elämään.",
				img: "Lennolilla uskomme, että koti heijastaa kaikkea, mikä tekee elämästä kaunista. Siksi jokaisella on mielestämme lupa uneksia."
			},
			en: {
				desc: "",
				img: "Your home reflects all the beauty in your life. At Lennol we dare to dream."
			}
		}, {
			title: "Kupilka",
			url: "https://kupilka.fi/",
			img: "processwire-kupilka-2018",
			tech: "ProcessWire, PHP, SQL",
			fi: {
				desc: "Ekologiset ja kierrätettävät astiat, puukot ja tulukset ulkoiluhetkiin.",
				img: "Kierrätettävät astia, puukot ja tulukset."
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Omamuutto",
			url: "https://omamuutto.fi/",
			img: "processwire-omamuutto-2020",
			fi: {
				desc: "Palvelu- ja omatoimimuutot sekä muuttotarvikkeet kätevästi verkkokaupasta.",
				img: "Omamuutto tarjoaa muuttotarvikkeet ja muuttajat kätevästi verkkokaupasta."
			},
			en: {
				desc: "",
				img: ""
			}
		}
	]
	let ref = "/images/references/ref-"
	let hero = "/images/webstore-page"
</script>

<svelte:head>
	<link rel="stylesheet" href="/page.css"> 
</svelte:head>

<div id="page">

<section id="about" class="twoGrid">
	<div class="img">
		<picture>
			<source srcset={hero +"-mobile.webp"} media="(max-width:999px)" type="image/webp">
			<source srcset={hero +".webp"} media="(min-width:1000px)" type="image/webp">
			<source srcset={hero +"-mobile.jpg"} media="(max-width:999px)" type="image/jpeg">
			<source srcset={hero +".jpg"} media="(min-width:1000px)" type="image/jpeg">
			<img src={hero +".jpg"} alt={title}>
		</picture>
	</div>
	<div class="txt cell mxa">
		<div class="content">
			<h1 class="effra title">Myyntiä 24/7 vaikka ympäri maailman</h1>
			<p>Mitä jos pistetään pakettiin erittäin kustannustehokas verkkokauppa, joka taipuu yrityksesi tarpeiden mukaan ja joka on räätälöity juuri sinun yritykselle? Meiltä verkkokauppa täysin "Avaimet käteen"-palveluna, jossa teema, tuotteet ja kaikki sisältö ovat valmiina. Sinun tarvitsee vain haaveille ja me toteutamme unelmasi.</p>
			<p>Olipa kyseessä meidän SaaS-palvelu ProcessWirelle tai WordPress-sivuston Woocommerce, saat aina mutkattoman ja toimivan ratkaisun.</p>
			<p>Ota rohkeasti yhteyttä ja tilaa ilmainen kartoitus nykyiseen verkkokauppaan tai suunnitelma uuteen.</p>
			<p><a class="btn up" href="/yllapito">Kauppa kuntoon!</a></p>
		</div>
	</div>
</section>

<section class="p3">
	<div class="container mxa small">
		<h2 class="effra sub1 tc m1">Kauppa, josta asiakkaasi lähtee ostoskassi mukanaan</h2>
		<p>Verkkokaupassa teknisen toteutuksen lisäksi on hyvä huomioida visuaalisuus sekä tuotteiden kertova ja informatiivinen teksti. Tuotekuvilla ja videoilla on myös suuri merkitys, sillä asiakas ostaa tuotteen varmemmin, mitä enemmän ostopäätöstä vahvistavaa tietoa siitä on tarjolla. Tekstin pitäisi olla myös mahdollisimman uniikkia sisältäen sopivasti avainsanoja. Kyllä, mahdollisimman hyviä hakusanoja pitäisi olla otsikoissa, osoitteissa ja tuotetekstissä.</p>
		<p>Kuulostaako vaikealle? Ei hätää, meidän kautta on mahdollista tilata myös tuotekuvat ja hyvin optimoidut tekstit tuotesivuille ja muualle kauppaan. Miksi tuhlata omaa aikaa miettimiseen, jos voi jättää ongelmat ammattilaiselle ja keskittyä omaan ydinbisnekseen?</p>
		<p>Ennen projektin alkua määrittelemme tarkkaan mitkä ovat sinun unelmasi ja teemme tarjouksen sen perusteella. Tarvittaessa graafkko tekee teemasta luonnoksen minkä perusteella koodarit koodaavat siitä kauniin, nopean ja helposti päivitettävän kokonaisuuden. Emme käytä valmiita teemoja vaan räätälöimme koodin juuri sinulle ja olemme henkilökohtaisesti vastuussa sen toimivuudesta. Lopputulos on viisaasti rakennettu myyntikanava eikä vain teknisesti kaunis toteutus.</p>
		<p>Haluamme kannustaa sinua kansainväliseen kauppaan, joten meidän kauppaan rajoittamattomasti tuotteita ja kieliä ilman lisämaksua. Valmiit integraatiot löytyvät yleisimmille maksuliikenteen tarjoajille emmekä rajoita kuljetusyhtiöitä. Kysy meiltä parhaat kumppanit juuri sinun tarpeisiin.</p>
		<p>Maksatko liikaa nykyisestä verkkokaupasta? Onko verkkokauppa viimeisen päälle optimoitu vai voisiko jotain vielä parantaa? Alkaako vanha verkkokauppa olemaan liian kankea tulevaisuuden kasvulle? Tarvitsetko integraation? Tilaa ilmainen tilanteen kartoitus ja keskustellaan miten voisimme auttaa sinua myymään paremmin.</p>
		<p><a class="btn up" href="/yllapito">Ota yhteyttä</a></p>
	</div>
</section>

<section class="p3">
	<div class="container mxa small tc"><h2 class="effra sub1">Muutama esimerkki ylpeydenaiheistamme</h2><p>Liitetäänkö sinunkin yrityksesi tähän huippujoukkueeseen?</p></div>
	<div id="references" class="container mxa fluid">
	{#each refs as item}
		<a class="ref block mxa" href={item.url} title={item.title} target="_blank" rel="noopener">
			<figure class="rel">
				<picture>
					<source srcset={ref + item.img +".webp"} type="image/webp">
					<source srcset={ref + item.img +".webp"} type="image/webp">
					<img src={ref + item.img +".webp"} alt={item.fi.img}>
				</picture>
				<figcaption class="bgw">
					<h2 class="effra">{item.title}</h2>
					<p>{item.fi.desc}</p>
				</figcaption>
			</figure>
		</a>
	{/each}
	</div>
</section>

<Hosting/>

</div>