<script>
	import { scrollto } from "svelte-scrollto"
	let services = [
		{
			title: "Verkkotohtorointi",
			summary: "Kaipaako yrityksesi uutta verkkosivustoa tai vanha huoltotoimenpiteitä? Toteutan kaikki projektit ketterästi ja kilpailukykyisellä hinnalla 'avaimet käteen'-periaatteella asiakkaan kaikkien toiveiden mukaisesti. Uusi verkkosivusto on responsiivinen, hakukoneoptimoitu, nopea ja helposti päivitettävä.",
			id: "websites",
			alt: "Responsiiviset ja kauniit verkkosivut yritykselle"
		}, {
			title: "Verkkokaupat",
			summary: "Tehosta myyntiä Tuspen monipuolisella verkkokaupalla Suomessa ja ulkomailla kilpailukykyiseen hintaan. Verkkokauppa kustomoidaan vastaamaan asiakkaan tarpeita, jonka lisäksi kaupassa on tarjolla rajattomasti kieli, tehokkaat kampanjat sekä tietenkin yleisimmät maksuvaihtoehdot ja kuljetukset.",
			id: "tuspeshop",
			alt: "Tehosta myyntiä paremmalla verkkokaupalla"
		}, {
			title: "Ratsukko",
			summary: "Oletko saanut tarpeeksi soitoista ja sähköposteista talliyrittäjänä tai tallin asiakkaana? Ei hätää! Varauskalenteri Ratsukko säästää aikaa ja vaivaa tarjoten reaaliaikaisen järjestelmän missä asiakkaat voivat itse hoitaa tuntien varaukset ja poistot. Hyppää ratsaille kohti helpompaa arkea!",
			id: "ratsukko",
			alt: "Varauskalenteri Ratsukko säästää aikaa, vaivaa ja rahaa!"
		}, {
			title: "Urheiluseurat",
			summary: "Monipuolisilla ominaisuuksilla varustettu urheilualusta sopii kaiken kokoisille urheiluseuroille. Tarvittaessa mukaan myös verkkokauppa. Päivitys helppoa ja nopeaa sekä olemme automatisoineet mahdollisimman paljon toimintoja. Oletko valmis lähtemään mukaan voittajan tiimiin?",
			id: "sport",
			alt: "Monipuolinen kotisivu urheiluseuralle"
		}, {
			title: "Hakukoneoptimointi",
			summary: "Kaikki projektit on teknisesti optimoitu hakukoneille ja vierailijoille, mutta sisältö on tärkein ja sen pitää olla uniikkia! Tarjoan vinkkejä miten voisit paremmin optimoida verkkosivustosi sekä verkoston kautta löytyy myös tarvittaessa ammattilainen kehittämään verkkosivuston sisältöä.",
			id: "seo",
			alt: "Tietoa teknisestä hakukoneoptimoinnista ja hakusanatutkimuksesta"
		}, {
			title: "Ylläpito",
			summary: "Dedikoidut palvelimme on suojattu teknisiltä ongelmilta sekä kaikki data varmuuskopioidaan kahdesti päivässä ulkoiselle palvelimelle. Turvallinen ja luotettava koti verkkosivustolle sekä samaan hintaan turvallisuuspäivitykset moduuleille ja pienet muutokset verkkosivustolle.",
			id: "hosting",
			alt: "Turvallinen ja luotettava koti verkkosivulle"
		}
	]
	let latest = [
		{
			site: "KoneJönnit",
			what: "Verkkosivusto, Nettix",
			partners: "Molentum Oy",
			link: "https://www.konejonnit.fi/",
			img: "processwire-konejonnit-2020",
			img_alt: "Joensuussa sijaitseva täyden palvelun koneliike. Pienkoneet puutarhaan, metsään, vesille ja teille! Ammattitaitoinen huolto- ja varaosapalvelu!"
		}, {
			site: "Omamuutto",
			what: "Verkkokauppa, vuokraus",
			partners: "Molentum Oy",
			link: "https://omamuutto.fi/",
			img: "processwire-omamuutto-2020",
			img_alt: "MUUTA omatoimisesti KUNNON VÄLINEILLÄ tai ammattilaisten avustuksella. VAIVATTOMASTI."
		}, {
			site: "NavyBlue Shop",
			what: "Verkkokauppa, Lemonsoft",
			partners: "Dataline Group Oy",
			link: "https://navyblue.fi/",
			img: "processwire-navyblue-2020",
			img_alt: "Aktiivisten ihmisten merkkivaate- ja kenkämyymälä."
		}, {
			site: "Lennol",
			what: "Verkkokauppa, Lemonsoft",
			partners: "Dataline Group Oy",
			link: "https://lennol.fi/",
			img: "processwire-lennol-2019",
			img_alt: "Your home reflects all the beauty in your life. At Lennol we dare to dream."
		}
	]
	let title = "Tuspe Design Oy"
	let summary = "Digitoimisto Tuspe Design Oy toteuttaa yritykselle upeat visuaaliset ja asiakkaita puhuttelevat verkkosivut sekä varmistaa sivuston näkyvyyden hakukoneoptimoinnilla."
	let img_alt = "Tuspe Design Oy toteuttaa yrityksesi verkkokaupan, verkkosivut ja kaiken siihen liittyvän."
</script>

<svelte:head>
    <title>{title} - Se parempi digitoimisto</title>
	<meta name="description" content={summary}>
	<meta property="og:site_name" content={title}>
	<meta property="og:title" content={title}>
	<meta property="og:image:alt" content={img_alt}>
	<meta property="og:description" content={summary}>
	<meta name="twitter:title" content={summary}>
	<meta name="twitter:description" content={summary}>
	<meta name="twitter:image:alt" content={img_alt}>
</svelte:head>

<section id="hero">
	<picture>
		<source srcset="/images/tuspe-laptop-667.webp 667w,/images/tuspe-laptop-768.webp 768w,/images/tuspe-laptop-1080.webp 1080w" type="image/webp">
		<source srcset="/images/tuspe-laptop-667.jpg 667w,/images/tuspe-laptop-768.jpg 768w,/images/tuspe-laptop-1080.jpg 1080w" type="image/jpg">
		<img src="/images/tuspe-laptop-1080.jpg" alt="Verkkosivut yritykselle nopeasti ja ammattitaidolla">
	</picture>
	<div id="caption" class="cell">
		<div class="content">
			<h1 class="tw"><span>Valloita nettimarkkinat</span> laadukkailla ratkaisuilla ja vahvalla brändillä</h1>
			<div id="links">
				<a class="btn tw" use:scrollto={'#contact'} href="/#contact" title="Keskutellaan miten voimme parantaa teidän myyntiä">Ota yhteyttä</a>
				<a class="btn tw" use:scrollto={'#partner'} href="/#partner" title="Etsitkö tekijää projekteille?">Kumppaniksi</a>
			</div>
		</div>
	</div>
</section>

<section id="services">
	<div class="bgw pd">
		<div id="about" class="tc mx">
			<div class="cell">
				<h3>Sijoitus tulevaisuuteen</h3>
				<h2><span class="purple">Laadukkaat verkkosivut</span><br>ovat hyvää asiakaspalvelua</h2>
				<p>Tiedätkö, millainen asiakaskokemus syntyy verkkosivustollasi ja kuinka nopeasti kävijä löytää etsimänsä? Löytyykö verkkosivu hakukoneiden ensimmäiseltä sivulta? Jos pohdit näitä kysymyksiä, olet tullut oikeaan paikkaan. Mietitään yhdessä miten voimme parantaa teidän näkyvyyttä ja nostetaan verkkosivuston haku- ja myyntitulokset paremmaksi.</p>
			</div>
		</div>
	</div>
	<div id="featured" class="container mx">
		<div class="row">
			{#each services as item, i}
				<div class={"col-4 mb id-"+ i}>
					<div class="content bgw">
						<picture>
							<source srcset={"/images/work-"+ item.id +".webp"} type="image/webp">
							<source srcset={"/images/work-"+ item.id +".jpg"} type="image/jpeg">
							<img src={"/images/work-"+ item.id +".jpg"} alt={item.img_alt}>
						</picture>
						<div class="pad">
							<h3 class="sub">{item.title}</h3>
							<p>{item.summary}</p>
						</div>
					</div>
				</div>
			{/each}
		</div>
	</div>
</section>

<section id="latest" class="tc container mx">
	<div id="latest_info" class="tw mx">
		<h2>Uusimmat toteutukset</h2>
		<p>Viimeisimmät projektit missä olemme olleet kumppanien kanssa mukana. Toteutamme kymmeniä projekteja vuodessa.</p>
		<!-- <p><a class="btn tw" href="/referenssit" title="Tyytyväisiä asiakkaita">Tutustu referensseihin</a></p> -->
	</div>
	<div class="row">
		{#each latest as item}
			<a class="col-3 ref mb" href={item.link} target="_blank" rel="noopener">
				<figure class="content bgw">
					<picture>
						<source srcset={"/images/ref-"+ item.img +".webp"} type="image/webp">
						<source srcset={"/images/ref-"+ item.img +".jpg"} type="image/jpeg">
						<img src={"/images/ref-"+ item.img +".jpg"} alt={item.img_alt}>
					</picture>
					<figcaption>
						<h3 class="sub">{item.site}</h3>
						<div class="what"><small>{item.what}</small></div>
						<div class="partners"><small>{item.partners}</small></div>
					</figcaption>
				</figure>
			</a>
		{/each}
	</div>
</section>

<section id="partners" class="bgw">
	<div class="container mx">
		<div class="row">
			<div id="partner" class="col mb">
				<h3 class="sub">Palveluja alihankintana</h3>
				<p>Haluamme olla kumppaneita, ei kilpailijoita! Haemme aktiivisesti uusia kumppaneita asiakashankintaan ja erilaisten palveluiden toteuttamiseen. Haluamme tarjota asiakkaille mahdollisimman kattavan kokonaisuuden palveluita.</p>
				<p><a href="mailto:myynti@tuspe.com" title="Lähetä sähköpostia ja kehitetään palveluita yhdessä" rel="nofollow">Ota rohkeasti yhteyttä</a> ja kerro teidän ydinosaamisesta.</p>
			</div>
			<div id="internship" class="col mb">
				<h3 class="sub">Koulusta työharjoitteluun?</h3>
				<p>Haluamme olla aktiivisesti mukana nuorten oppimisessa ja uusien alan tähtien kehityksessä. Kysy harjoittelupaikkaa suoraan tai koulun kautta. Meillä pääsee koodaamaan ja ylläpitämään palveluita eikä tarvitse olla kantamassa kahvia!</p>
			</div>
		</div>
	</div>
</section>