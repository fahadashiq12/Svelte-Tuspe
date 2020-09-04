<script>
	import { metatags } from "@sveltech/routify"
	let title = "Verkkotunnuksen rekisteröinti eli domain kotisivulle"
	let desc = "Kotisivut ovat pelivälineesi digikentällä. Hyvin rakennetut ja toimivat sivut ovat ilo silmälle, aperitiivi ostohalulle sekä tehty maali asiakkaan bisnekseen."
	let url = "https://tuspe.com/verkkotunnukset"
	metatags.title = title +" | Tuspe Design"
	metatags.description = desc
	metatags.url = url
	metatags.canonical = url
	metatags["twitter:card"] = "summary_large_image"
	metatags["twitter:title"] = title
	metatags["twitter:description"] = desc
</script>

<svelte:head>
	<link rel="stylesheet" href="/page.css"> 
</svelte:head>

<div id="page">

<section id="about" class="twoGrid">
	<div class="img">
		<picture>
			<source srcset="/images/websites-page-mobile.webp" media="(max-width:760px)" type="image/webp">
			<source srcset="/images/websites-page.webp" media="(min-width:761px)" type="image/webp">
			<source srcset="/images/websites-page-mobile.jpg" media="(max-width:760px)" type="image/jpeg">
			<source srcset="/images/websites-page.jpg" media="(min-width:761px)" type="image/jpeg">
			<img src="/images/websites-page.jpg" alt={title}>
		</picture>
	</div>
	<div class="txt cell mxa">
		<div class="content">
			<h1 class="effra title">Verkkotunnus</h1>
			<p>Verkkotunnus eli domain on sivujesi nimi ja osoite. Jos sinulla ei vielä ole verkkotunnusta, olet päätynyt oikeaan paikkaan. Meidän kauttamme voit varata erittäin kilpailukykyisellä hinnalla minkä tahansa päätteen. Olemme Traficomin jälleenmyyjä eli myös fi-tunnukset.</p>
			<p>Meiltä saat verkkotunnuksen myös ilman muita sopimuksia sekä ilmaiset nimipalvelimet tarvittaessa sekä voimme siirtää verkkotunnuksen nykyiseltä palveluntarjoajalta meille ilman lisäkustannuksia.</p>
			<p>Olipa tarpeesi mikä tahansa, me hoidamme sen puolestasi.</p>
			<p><a class="btn up" href="/yllapito">Nimet kuntoon!</a></p>
		</div>
	</div>
</section>

<section class="p3">
	<div class="container mxa small">
		<h2 class="effra sub1 tc m1">Huolehdimme kaiken valmiiksi</h2>
		<ul class="ml"><li>Verkkotunnuksen rekisteröinti sinun tiedoillasi (<a href="https://www.traficom.fi/fi/viestinta/fi-verkkotunnukset/fi-verkkotunnushaku" title="Tarkista, onko haluamasi fi-verkkotunnus vapaana." target="_blank" hreflang="fi">Traficom</a> / <a href="https://www.namecheap.com/" title="Tarkista, onko haluamasi verkkotunnus vapaana." target="_blank" hreflang="en">Namecheap</a>).</li><li>Uusimme vuosittain verkkotunnuksen automaattisesti.</li><li>Ilmaiset nimipalvelimet tarvittaessa (<a href="https://www.cloudflare.com/" title="Suojaa palvelusi Cloudflaren avulla" target="_blank" hreflang="en">Cloudflare</a>).</li><li>Sähköpostiasiat kuntoon.</li><li>Verkkotunnuksien rekisteröinnissä mahdollisimman halvat hinnat sekä mahdollisesti muita rahan arvoisia vinkkejä tulevaisuudelle.</li></ul>
		<p>Emme usko määräaikaisiin sopimuksiin vaan verkkotunnus on aina sinun eli voit koska tahansa siirtää verkkotunnuksen meiltä toiselle palveluntarjoajalle tai vaihtaa haluamasi nimipalvelimet siihen.</p>
		<p>Hoidamme tarvittaessa myös yrityksesi sähköpostipalvelut kuntoon. Meiltä onnistuvat omalla verkkotunnuksella ilmaiset Gmail tai Outlook sekä maksulliset <a href="https://gsuite.google.fi/intl/fi/" title="Tuttu ja turvallinen Gmail yritysten tarpeisiin räätälöitynä." hreflang="fi">GSuite</a> tai <a href="https://www.office.com/?omkt=fi-FI" title="Sähköposti ja Office-sovellusten Premium-versiot" hreflang="fi">Office 365</a>. Myös käyttöopastusta.</p>
		<p>Riippumatta siitä kuka huolehtii kotisivujen hyvinvoinnista, suosittelemme käyttämään maksutonta Cloudflare-palvelua (mm. nimipalvelut, kotisivujen suojaus, parempi välimuisti), koska sen avulla on mahdollista nopeuttaa huomattavasti kansainvälistä liikennettä sivustolla sekä suojata yrityksen kotisivut paremmin mahdollisilta palvelunestohyökkäyksiltä. Cloudflarella on palvelimia ympäri maailman, joten jos sivustosi käyttää heidän välimuistia vierailija vierailee todellisuudessa lähimmällä serverillä mikä saattaa vähentää huomattavasti latausaikaa.</p>
	</div>
</section>

</div>