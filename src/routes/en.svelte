<script>
	let title = "Tuspe Design | Website for company"
	let summary = "Tuspe is a Rauma based company specialized in designing and implementing websites and e-commerce stores as well as expert Google search engine optimization."
</script>

<svelte:head>
	<title>Tuspe Design | Responsive and fast website for your business</title>
	<meta name="description" content={summary}>
	<meta property="og:title" content={title}>
	<meta property="og:description" content={summary}>
	<meta property="og:image:alt" content={title}>
	<meta name="twitter:description" content={summary}>
	<meta name="twitter:title" content={title}>
	<meta name="twitter:image:alt" content={title}>
</svelte:head>

<div id="hero" class="rel acme obj">
    <div id="caption" class="cell tc abs">
        <div class="text-white mini">
            <h1 class="title mb-4">Tuspe Design</h1>
            <p>{summary}</p>
        </div>
    </div>
	<picture>
		<source srcset="/assets/images/hero.webp" type="image/webp">
		<source srcset="/assets/images/hero.jpg" type="image/jpeg">
		<img src="/assets/images/hero.jpg" alt="Responsive and fast website for your business">
	</picture>
</div>

<div id="line" class="contact">
    <div class="wrap tc">
        <ul class="socialmedia mx-auto text-white">
            <li class="inl"><a id="mobile" class="block circle text-white" href="tel:+358407746121" rel="nofollow noopener noreferrer" title=""><div class="cell icon icon-mobile"></div><span class="hidden"></span></a></li>
            <li class="inl"><a id="mail" class="block circle text-white" href="mailto:info@tuspe.com" rel="nofollow noopener noreferrer" title=""><div class="cell icon icon-mail"></div><span class="hidden"></span></a></li>
            
            <li class="inl"><a class="block circle text-white" href="https://www.linkedin.com/in/anttilatimo/" title="Linkedin" target="_blank" rel="me noopener"><div class="cell icon icon-linkedin"></div><span class="hidden">Linkedin</span></a></li>
            
            <li class="inl"><a class="block circle text-white" href="https://www.facebook.com/tuspedesign" title="Facebook" target="_blank" rel="me noopener"><div class="cell icon icon-facebook"></div><span class="hidden">Facebook</span></a></li>
            
            <li class="inl"><a class="block circle text-white" href="https://twitter.com/tuspedesign" title="Twitter" target="_blank" rel="me noopener"><div class="cell icon icon-twitter"></div><span class="hidden">Twitter</span></a></li>
            
            <li class="inl"><a class="block circle text-white" href="https://github.com/tewdin" title="Github" target="_blank" rel="me noopener"><div class="cell icon icon-github"></div><span class="hidden">Github</span></a></li>
            
        </ul>
    </div>
</div>
<section id="hello" class="container mini text-white mbot">
    <h2 class="subtitle tc">Hey, I'm Timo. Nice to meet you.</h2>
	<p>I've designed and created websites for several communities and my own needs since 1999. I started to make websites for living in 2014 when <a href="https://molentum.fi/" target="_blank" title="Partner: Molentum Oy" rel="noreferrer noopener">Molentum Oy</a> hired me. A couple of years later, in 2016, I founded my own company Tuspe and nowadays I work full time through Tuspe for Molentum. Time to time I do some projects for Dataline (web shops and sport platforms) and develop <a href="https://www.ratsukko.com/" target="_blank" title="Ratsukko - Booking calendar for riders" rel="noreferrer noopener">Ratsukko booking system</a> for <a href="https://www.satumo.fi/en/" target="_blank" title="Partner: SatuMo Oy" rel="noreferrer noopener">SatuMo Oy</a>.</p>

<p>My specialities are HTML5, CSS3, AMP HTML -mobile optimization technique, PHP and search engine optimization. I also have basic knowlegde of photography, photo editing and video creation. I follow the latest trends from the world, and by that my customers can be the forerunners in their field and communicate in a modern way. My goal is satisfied customers and long customer relationships and offer 100% satisfaction guarantee for all of my projects.</p>
<p><a href="mailto:info@tuspe.com" rel="nofollow" title="Send emails"> Feel free to contact me</a> if you are looking for a website or are interested in working together.</p> <div id = "business_contact" class = "tc mt-4 pt-3"> <a class="text-white" href="tel:+358407746121" rel="nofollow"> 040 774 6121 </a> | <a class="text-white" href="mailto:info@tuspe.com" rel="nofollow"> info@tuspe.com </a> <br> 2745877-5 </div>
</section>

<div class="bg-white"><div class="container pb-5">

<section id="projects" class="row text-white rel mtop">
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-websites.webp" type="image/webp">
				<source srcset="/assets/images/work-websites.jpg" type="image/jpeg">
				<img src="/assets/images/work-websites.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Verkkotohtorointi</h3>
                <div class="summary"><p>Kaipaako yrityksesi uutta verkkosivustoa tai vanha huoltotoimenpiteitä?<br>Toteutan kaikki projektit ketterästi ja kilpailukykyisellä hinnalla 'avaimet käteen'-periaatteella asiakkaan kaikkien toiveiden mukaisesti. Uusi verkkosivusto on responsiivinen, hakukoneoptimoitu, nopea ja helposti päivitettävä.</p></div>
            </div>
        </div>
    </div>
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-webshops.webp" type="image/webp">
				<source srcset="/assets/images/work-webshops.jpg" type="image/jpeg">
				<img src="/assets/images/work-webshops.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Verkkokaupat</h3>
                <div class="summary"><p>Tehosta myyntiä Tuspen monipuolisella verkkokaupalla Suomessa ja ulkomailla kilpailukykyiseen hintaan. Verkkokauppa kustomoidaan vastaamaan asiakkaan tarpeita, jonka lisäksi kaupassa on tarjolla rajattomasti kieli, tehokkaat kampanjat sekä tietenkin yleisimmät maksuvaihtoehdot ja kuljetukset.</p></div>
            </div>
        </div>
    </div>
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-ratsukko.webp" type="image/webp">
				<source srcset="/assets/images/work-ratsukko.jpg" type="image/jpeg">
				<img src="/assets/images/work-ratsukko.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Ratsukko</h3>
                <div class="summary"><p>Oletko saanut tarpeeksi soitoista ja sähköposteista talliyrittäjänä tai tallin asiakkaana? Ei hätää! Varauskalenteri Ratsukko säästää aikaa ja vaivaa tarjoten reaaliaikaisen järjestelmän missä asiakkaat voivat itse hoitaa tuntien varaukset ja poistot. Hyppää ratsaille kohti helpompaa arkea!</p></div>
            </div>
        </div>
    </div>
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-sport.webp" type="image/webp">
				<source srcset="/assets/images/work-sport.jpg" type="image/jpeg">
				<img src="/assets/images/work-sport.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Urheilu</h3>
                <div class="summary"><p>Monipuolisilla ominaisuuksilla varustettu urheilualusta sopii kaiken kokoisille urheiluseuroille. Tarvittaessa mukaan myös verkkokauppa. Päivitys helppoa ja nopeaa sekä olemme automatisoineet mahdollisimman paljon toimintoja. Oletko valmis lähtemään mukaan voittajan tiimiin?</p></div>
            </div>
        </div>
    </div>
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-seo.webp" type="image/webp">
				<source srcset="/assets/images/work-seo.jpg" type="image/jpeg">
				<img src="/assets/images/work-seo.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Hakukoneoptimointi</h3>
                <div class="summary"><p>Kaikki projektit on teknisesti optimoitu hakukoneille ja vierailijoille, mutta sisältö on tärkein ja sen pitää olla uniikkia! Tarjoan vinkkejä miten voisit paremmin optimoida verkkosivustosi sekä verkoston kautta löytyy myös tarvittaessa ammattilainen kehittämään verkkosivuston sisältöä.</p></div>
            </div>
        </div>
    </div>
    
    <div class="col-4 r12 r7 mb-4">
        <div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-hosting.webp" type="image/webp">
				<source srcset="/assets/images/work-hosting.jpg" type="image/jpeg">
				<img src="/assets/images/work-hosting.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
            <div class="p-4">
                <h3 class="subtitle">Ylläpito</h3>
                <div class="summary"><p>Dedikoidut palvelimme on suojattu teknisiltä ongelmilta sekä kaikki data varmuuskopioidaan kahdesti päivässä ulkoiselle palvelimelle. Turvallinen ja luotettava koti verkkosivustolle sekä samaan hintaan turvallisuuspäivitykset moduuleille ja pienet muutokset verkkosivustolle.</p></div>
            </div>
        </div>
    </div>
    
</section>

<section id="contact" class="contact container bor tc pt-4 pb-4">
    <div class="row text-white">
        <div class="col-3 r1 mb1"><div class="cell"><h4 class="acme">Uusi projekti?</h4></div></div>
        <div class="col-6 r1 mb1"><div class="cell"><div class="content">Kiinnostaako yhteistyö? Ota yhteyttä ja keskustellaan miten voin auttaa.</div></div></div>
        <div class="col-3 r1"><div class="cell"><a class="inl text-white" href="mailto:info@tuspe.com" rel="nofollow">info@tuspe.com</a><a class="inl text-white" href="tel:+358407746121" rel="nofollow">040 774 6121</a></div></div>
    </div>
</section>

</div></div>