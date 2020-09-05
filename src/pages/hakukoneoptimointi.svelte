<script>
	import { metatags } from "@sveltech/routify"
	let title = "Kotisivut yritykselle ketterästi ja ammattitaidolla"
	let desc = "Kotisivut ovat pelivälineesi digikentällä. Hyvin rakennetut ja toimivat sivut ovat ilo silmälle, aperitiivi ostohalulle sekä tehty maali asiakkaan bisnekseen."
	let img = "https://timoanttila.com/images/gallery/2019-deli-yawns.jpg"
	let url = "https://tuspe.com/referenssit"
	metatags.title = title +" | Tuspe Design"
	metatags.description = desc
	metatags.image = img
	metatags.url = url
	metatags.canonical = url
	metatags["twitter:card"] = "summary_large_image"
	metatags["twitter:title"] = title
	metatags["twitter:description"] = desc
	metatags["twitter:image"] = img
</script>

<svelte:head>
	<link rel="stylesheet" href="/page.css"> 
</svelte:head>

<div id="page">

<section id="about">
	<div class="img">
		<picture>
			<source srcset="/images/websites-page-mobile.webp" media="(max-width:999px)" type="image/webp">
			<source srcset="/images/websites-page.webp" media="(min-width:1000px)" type="image/webp">
			<source srcset="/images/websites-page-mobile.jpg" media="(max-width:999px)" type="image/jpeg">
			<source srcset="/images/websites-page.jpg" media="(min-width:1000px)" type="image/jpeg">
			<img src="/images/websites-page.jpg" alt={title}>
		</picture>
	</div>
	<div class="txt cell mxa">
		<div class="content">
			<h1 class="w3">Hakukoneoptimointi</h1>
			<p>Meidän kaikki sivustomme on teknisesti automaattisesti optimoituja parhaalla mahdollisella tavalla, samalla tavalla kuin esim. WordPress tarjoaa siihen tarkoitetuilla lisäosillaan. Valitettavasti hakukoneoptimointi on paljon muutakin kuin pelkkää teknistä osaamista. SISÄLTÖ ON KINGI!</p>
			<p>Otsikoissa ja sisältöteksteissä tulisi olla sopiva määrä hakusanoja, avainsanoja, luomassa parempia hakutuloksia sekä niiden tulisi olla mahdollisimman uniikkeja. Verkkokaupan tuotteet voivat olla samoja kuin kymmenillä tai sadoilla kilpailijoilla, joten miten juuri sinun tuotteesi erottautuvat joukosta?</p>
			<p><a class="btn up" href="/yllapito">Hakukoneita viettelemään!</a></p>
		</div>
	</div>
</section>

<section class="p3">
	<div class="container mxa small">
		<h2 class="w3 sub1 tc">Mitä hakukoneoptimointi tarkoittaa ja mikä on avainsanatutkimus?</h2>
		<p>Hakukoneoptimointi (SEO) on sivuston näkyvyyden parantamista hakukonetuloksissa orgaanisen, eli maksuttoman, liikenteen osalta. Hakukoneoptimointi on kustannustehokasta, sillä hyvin optimoitu sivusto löytyy hakukoneista oikeilla hakusanoilla riittävän korkealta orgaanisesti ja se saa myös maksetussa hakukonemainonnassa paremmat laatupisteet.</p>
		<p>Hakukoneoptimointiin kiinteästi liittyvä avainsanatutkimus kannattaa tehdä jo kotisivujen ja verkkokaupan suunnitteluvaiheessa. Avainsanatutkimuksella selvitetään, miten paljon hakuja tehdään tietyillä sanoilla yrityksesi toimialalla ja tuotteisiin tai palveluihin liittyen. Kun volyymiltaan suurimmat avainsanat on selvitetty, upotetaan ne kotisivujesi tai verkkokauppasi sisältöteksteihin. Näin mahdollistetaan kotisivujesi sekä sen alasivujen löytyminen potentiaalisille asiakkaillesi.</p>
		<p>Vaikka kotisivusi ja verkkokauppasi olisivat visuaalisesti ja rakenteeltaan upeat ja lyömättömät, eivät asiakkaasi välttämättä löydä sivuja, jollei niitä ole hakukoneoptimoitu.</p>
		<p>Onko sinulla jo valmiit kotisivut tai verkkokauppa, joiden sisältöä olisi syytä tarkistaa? Kysy kattavaa analyysia sivujesi nykyisestä tilanteesta. Tarkistetaan, ovatko sivusi hakukoneoptimoidut ja miten sivujen tehokkuutta voisi parantaa. Saat myös tekniset parannukset jo olemassa olevaan sivustoon.</p>
	</div>
</section>

</div>