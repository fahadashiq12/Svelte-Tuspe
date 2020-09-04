<script>
	import { metatags } from "@sveltech/routify"
	import Hosting from "../components/Hosting.svelte"
	let refs = [
		{
			title: "Venehotelli",
			url: "https://venehotelli.fi/",
			img: "processwire-venehotelli-2020",
			tech: "ProcessWire, PHP",
			fi: {
				desc: "Veneiden talvisäilytys ja huollot helposti kuin hotellissa.",
				img: "Venehotelli Inkoo tarjoaa veneiden talvisäilytykset ja huollot"
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Ratsukko",
			url: "https://www.ratsukko.com/",
			img: "processwire-ratsukko-2020",
			fi: {
				desc: "Varauskalenteri Ratsukko on talliyrittäjän tallitoiminnan kokonaisvaltainen työkalu.",
				img: "Uudet kotisivut varauskalenteri Ratsukkolle"
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Quje",
			url: "https://quje.fi/",
			img: "processwire-quje-2020",
			fi: {
				desc: "Helppo tapa tavoittaa asiakkaat some-kanavissa sekä löytää yhteistyökumppaneita.",
				img: "Löydä uusia asiakkaita ja kumppaneita somesta"
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Hamari",
			url: "https://www.hamari.pro/",
			img: "processwire-hamari-2018",
			fi: {
				desc: "Suuria oivalluksia auditoriotiloihin tiiviissä paketissa.",
				img: "Kotimaisiin auditoriokalusteisiin erikoistunut suomalaisyritys."
			},
			en: {
				desc: "",
				img: ""
			}
		}
	]
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
			<source srcset="/images/websites-page-mobile.webp" media="(max-width:760px)" type="image/webp">
			<source srcset="/images/websites-page.webp" media="(min-width:761px)" type="image/webp">
			<source srcset="/images/websites-page-mobile.jpg" media="(max-width:760px)" type="image/jpeg">
			<source srcset="/images/websites-page.jpg" media="(min-width:761px)" type="image/jpeg">
			<img src="/images/websites-page.jpg" alt={title}>
		</picture>
	</div>
	<div class="txt cell mxa">
		<div class="content">
			<h1 class="effra title">Suunnittelua ja toteutusta suurella sydämellä</h1>
			<p>Tehdäänkö asioista helppoa ja sujuvaa? Verkkoviidakossa suunnistamisen ei tarvitse olla hankalaa ja aikaa vievää. Jos haluat yrityksesi koko verkkonäkyvyyden kerralla kuntoon, olet juuri nyt oikeassa osoitteessa.</p>
			<p>Kokemus, aito into ja asiakkaiden toimeksiannot sydämellä tehtynä luovat tekemisemme moottorin. Emme lupaa kuuta taivaalta, mutta meillä kotisivusi ja verkkokauppasi suunnittelu ja toteutus ovat luotettavissa käsissä.</p><p>Paiskataanko kättä ja laitetaan hihat heilumaan?</p>
			<p><a class="btn up" href="/yhteys">Luodaan fiiliksiä!</a></p>
		</div>
	</div>
</section>

<section class="p3">
	<div class="container mxa small">
		<h2 class="effra sub1 tc m1">Avaimet käteen</h2>
		<p>Se tunne, kun jäät koukkuun hyvään kirjaan tai sarjaan.. Mitäs jos luotaisiin sama fiilis asiakkaallesi kotisivuistasi?</p>
		<p>Olipa kyseessä kotisivut tai <a href="/verkkokauppa-yritykselle">verkkokauppa yrityksellesi</a>, saat meiltä avaimet käteen-ratkaisun. Lopputulos ei ole pelkkä teknisesti kaunis toteutus vaan viisaasti rakennettu myyntikanava, jonka sisältö ja ulkoasu puhuttelevat asiakkaitasi juuri oikealla tavalla. Luodaan sinun yrityksen näköinen kotisivu.</p>
		<p>Kotisivuilla on suuri merkitys edelleen tämän päivän digimaailmassa. Kotisivu on alusta, jossa kerrot yrityksesi tarinan ja saat asiakkaasi kiinnostumaan tuotteistasi ja palveluistasi. Se on myyntikanava ja yrityksesi kotipaikka verkossa. Somekanavat voivat tukea myyntiä ja näkyvyyttä, mutta omat kotisivut tiivistää kaiken yhteen paikkaan.</p>
		<p>Kun mietit yhteistyökumppania kotisivujesi tekijälle, huomio suunnittelussa, toteutuksessa ja hinnassa, mitä kaikkea todellisuudessa saat:</p>
		<ol class="m0">
			<li>Tarvitsetko vain teknisen ratkaisun, jonne tuotat itse sisällön?</li>
			<li>Mitä analytiikkatyökaluja tarvitaan, jotta asiakkaasi ja sidosryhmäsi löytävät yrityksesi tuotteet ja palvelut?</li>
			<li>Mikä on <a href="/hakukoneoptimointi">avainsanatutkimus</a>? Erittäin tärkeä sisällön suunnittelun lähtökohta, jossa kotisivujesi kertova teksti optimoidaan niin, että asiakkaasi löytävät hakemillaan sanoilla hakukoneiden kautta juuri sinun yrityksesi.</li>
			<li>Onko kotisivujen päivittäminen vaikeaa? Ei ole ja kyllä osaat, kun asiat kerrotaan ja opastetaan ymmärrettävästi sinulle kuten me teemme.</li>
			<li>Miten ja mistä hankkia <a href="/verkkotunnus">verkkotunnus</a> (domain)? Ei hätää, me hoidamme tarvittaessa kaiken puolestasi, jonka jälkeen verkkotunnuksen hallinta on joko sinun nimipalvelimilla tai meidän lisämaksuttomilla. Me emme veloita ryöstöhintoja verkkotunnuksen vuosimaksuista.</li>
			<li>Millaisia <a href="/yllapito">ylläpitopalveluita</a> tarvitsen?</li>
		</ol>
		<p>Et jää yksin näiden kysymysten kanssa vaan me olemme valmiit auttamaan sinut ylitse ongelmien. Laske alustava tarjous kotisivuillesi sen mukaan, miten kattavan kokonaisuuden haluat.</p>
	</div>
</section>

<section class="p3">
	<div class="container mxa small tc"><h2 class="effra sub1">Muutama esimerkki ylpeydenaiheistamme</h2><p>Liitetäänkö sinunkin yrityksesi tähän huippujoukkueeseen?</p></div>
	<div id="references" class="container mxa fluid">
	{#each refs as item}
		<a class="ref block mxa" href={item.url} title={item.title} target="_blank" rel="noopener">
			<figure class="rel">
				<picture>
					<source srcset={"/images/references/ref-"+ item.img +".webp"} type="image/webp">
					<source srcset={"/images/references/ref-"+ item.img +".webp"} type="image/webp">
					<img src={"/images/references/ref-"+ item.img +".webp"} alt={item.fi.img}>
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