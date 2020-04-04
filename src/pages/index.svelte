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
	let title = "Tuspe Design"
	let summary = "Tuspe on raumalainen verkkosivustojen ja verkkokauppojen suunnitteluun ja toteutukseen sekä asiantuntevaan Google-hakukoneoptimointiin erikoistunut yritys."
</script>

<svelte:head>
    <title>Tuspe Design - Se parempi digitoimisto</title>
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
		</div>
	</div>
	<div id="contactUs">
		<a href="tel:+358407746121" title="Keskutellaan miten voimme parantaa teidän myyntiä" rel="noopener nofollow">
			<div class="cell">
				<svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24"><path d="M19 2c0-1.104-.896-2-2-2h-10c-1.104 0-2 .896-2 2v20c0 1.104.896 2 2 2h10c1.104 0 2-.896 2-2v-20zm-8.5 0h3c.276 0 .5.224.5.5s-.224.5-.5.5h-3c-.276 0-.5-.224-.5-.5s.224-.5.5-.5zm1.5 20c-.553 0-1-.448-1-1s.447-1 1-1c.552 0 .999.448.999 1s-.447 1-.999 1zm5-3h-10v-14.024h10v14.024z"/></svg>
			</div>
		</a>
		<a href="mailto:myynti@tuspe.com" title="Lähetä rohkeasti viestiä" rel="noopener nofollow">
			<div class="cell">
				<svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24"><path d="M12.042 23.648c-7.813 0-12.042-4.876-12.042-11.171 0-6.727 4.762-12.125 13.276-12.125 6.214 0 10.724 4.038 10.724 9.601 0 8.712-10.33 11.012-9.812 6.042-.71 1.108-1.854 2.354-4.053 2.354-2.516 0-4.08-1.842-4.08-4.807 0-4.444 2.921-8.199 6.379-8.199 1.659 0 2.8.876 3.277 2.221l.464-1.632h2.338c-.244.832-2.321 8.527-2.321 8.527-.648 2.666 1.35 2.713 3.122 1.297 3.329-2.58 3.501-9.327-.998-12.141-4.821-2.891-15.795-1.102-15.795 8.693 0 5.611 3.95 9.381 9.829 9.381 3.436 0 5.542-.93 7.295-1.948l1.177 1.698c-1.711.966-4.461 2.209-8.78 2.209zm-2.344-14.305c-.715 1.34-1.177 3.076-1.177 4.424 0 3.61 3.522 3.633 5.252.239.712-1.394 1.171-3.171 1.171-4.529 0-2.917-3.495-3.434-5.246-.134z"/></svg>
			</div>
		</a>
	</div>
</section>

<section id="services">
	<div class="bgw pd">
		<div id="about" class="tc">
			<div class="cell">
				<h3>Sijoitus tulevaisuuteen</h3>
				<h2><span class="purple">Laadukkaat verkkosivut</span><br>ovat hyvää asiakaspalvelua</h2>
				<p>Tiedätkö, millainen asiakaskokemus syntyy verkkosivustollasi ja kuinka nopeasti kävijä löytää etsimänsä? Löytyykö verkkosivu hakukoneiden ensimmäiseltä sivulta? Jos pohdit näitä kysymyksiä, olet tullut oikeaan paikkaan. Mietitään yhdessä miten voimme parantaa teidän näkyvyyttä ja nostetaan verkkosivuston haku- ja myyntitulokset paremmaksi.</p>
				<p><a use:scrollto={'#contact'} class="btn tb" href="/#contact" title="Yhteystiedot">Ota yhteyttä</a></p>
			</div>
		</div>
	</div>
	<div id="featured" class="row mx w9">
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
</section>

<section id="latest" class="tc mx w9">
	<div id="latest_info" class="tw mx w9">
		<h2>Uusimmat toteutukset</h2>
		<p>Viimeisimmät projektit missä olemme olleet kumppanien kanssa mukana. Toteutamme kymmeniä projekteja vuodessa.</p>
		<!-- <p><a class="btn tw" href="/referenssit" title="Tyytyväisiä asiakkaita">Tutustu referensseihin</a></p> -->
	</div>
	<div class="row">
		{#each latest as item}
			<a class="col-3 ref mb" href={item.link} target="_blank" rel="noopener">
				<figure class="content">
					<picture>
						<source srcset={"/images/ref-"+ item.img +".webp"} type="image/webp">
						<source srcset={"/images/ref-"+ item.img +".jpg"} type="image/jpeg">
						<img src={"/images/ref-"+ item.img +".jpg"} alt={item.img_alt}>
					</picture>
					<figcaption class="bgw">
						<h3 class="sub">{item.site}</h3>
						<div class="what"><small>{item.what}</small></div>
						<div class="partners"><small>{item.partners}</small></div>
					</figcaption>
				</figure>
			</a>
		{/each}
	</div>
</section>

<section id="partners" class="bgw mx">
	<div class="inner mx w9">
		<div id="partner" class="row">
			<div class="col mb">
				<picture>
					<source srcset="/images/partners.webp" type="image/webp">
					<source srcset="/images/partners.jpg" type="image/jpeg">
					<img src="/images/partners.jpg" alt="">
				</picture>
			</div><div class="col mb"><div class="cell">
				<h3 class="sub">Palveluja alihankintana</h3>
				<p>Haluamme olla kumppaneita, emme kilpailijoita! Haemme aktiivisesti uusia kumppaneita asiakashankintaan ja erilaisten palveluiden toteuttamiseen.</p>
				<p><a href="mailto:myynti@tuspe.com" title="Lähetä sähköpostia ja kehitetään palveluita yhdessä" rel="nofollow">Ota rohkeasti yhteyttä</a> ja kerro teidän ydinosaamisesta ja miten voisimme kehittää yhteystyötä. Hyödynnä palveluidemme reilut kumppanuusalennukset.</p>
			</div></div>
		</div>
		<div id="internship" class="row rr">
			<div class="col mb">
				<picture>
					<source srcset="/images/internship.webp" type="image/webp">
					<source srcset="/images/internship.jpg" type="image/jpeg">
					<img src="/images/internship.jpg" alt="">
				</picture>
			</div><div class="col mb"><div class="cell">
				<h3 class="sub">Koulusta työharjoitteluun?</h3><p>Haluamme olla aktiivisesti mukana nuorten oppimisessa ja koululaiset voivat kysyä harjoittelupaikkaa suoraan tai koulun kautta. Meillä pääsee koodaamaan eikä tarvitse olla kantamassa kahvia!</p>
			</div></div>
		</div>
	</div>
</section>