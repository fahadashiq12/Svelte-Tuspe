<script>
	let title = "Tuspe Design | Responsive and beautiful websites"
	let summary = "Tuspe is a Rauma based company specialized in designing and implementing websites and e-commerce stores as well as expert Google search engine optimization."
</script>

<svelte:head>
	<title>{title}</title>
	<meta name="description" content={summary}>
	<meta property="og:title" content={title}>
	<meta property="og:description" content={summary}>
	<meta property="og:image:alt" content={title}>
	<meta name="twitter:description" content={summary}>
	<meta name="twitter:title" content={title}>
	<meta name="twitter:image:alt" content={title}>
	<link rel="canonical" href="https://tuspe.com/en/">
	<link rel="amphtml" href="https://amp.tuspe.com/en">
</svelte:head>

<a id="lang" class="acme text-white circle" href="/" hreflang="fi" rel="home">FI</a>

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

<div class="bg-white"><div class="container">

<section id="projects" class="row text-white rel mtop">
	
	<div class="col-4 r12 r7 mb-4">
		<div class="content bor rel h-100 bg norm">
			<picture>
				<source srcset="/assets/images/work-websites.webp" type="image/webp">
				<source srcset="/assets/images/work-websites.jpg" type="image/jpeg">
				<img src="/assets/images/work-websites.jpg" alt="Responsiivinen ja nopea verkkosivu yritykselle">
			</picture>
			<div class="p-4">
				<h3 class="subtitle">Websites</h3>
				<div class="summary"><p>Looking for a new website or an update to an old website? I execute all projects quickly and at a competitive price according to all clients' wishes. The new website is responsive, beautiful, search engine optimized, quick and easy to update.</p></div>
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
				<h3 class="subtitle">Web stores</h3>
				<div class="summary"><p>Boost sales with Tuspe's versatile online store platform at competitive prices. The web store is customized to meet the customer's needs, with unlimited language, effective campaigns, and of course the most common payment and shipping options.</p></div>
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
				<div class="summary"><p>Too many phone calls and emails on bookings as a stable entrepreneur? No worries! Reservation calendar Ratsukko saves time and effort by providing a real-time system where customers can take care of bookings and cancellations on their own.</p></div>
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
				<h3 class="subtitle">Sport Clubs</h3>
				<div class="summary"><p>Our website for sport clubs have versatile features and it's suitable for sports clubs of all sizes. You can even have web store included. Editing is easy and fast and we have automated as many functions as possible. Are you ready to join the winning team?</p></div>
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
				<h3 class="subtitle">Better Search Results</h3>
				<div class="summary"><p>All projects are technically optimized for search engines and visitors, but content is most important and must be unique! I offer tips on how to better optimize your website and your content if needed. Also recommend keyword research.</p></div>
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
				<h3 class="subtitle">Hosting</h3>
				<div class="summary"><p>Our dedicated servers are protected from technical problems and all your data is backed up twice a day to an external server. A secure and reliable home for your website, plus all security updates for modules and small changes to your website.</p></div>
			</div>
		</div>
	</div>
	
</section>

<section id="contact" class="contact container bor tc pt-4 pb-4">
	<div class="row text-white">
		<div class="col-3 r1 mb1"><div class="cell"><h4 class="acme">New project?</h4></div></div>
		<div class="col-6 r1 mb1"><div class="cell"><div class="content">Interested? Contact me and let's discuss how I can help.</div></div></div>
		<div class="col-3 r1"><div class="cell"><a class="inl text-white" href="mailto:info@tuspe.com" rel="nofollow">info@tuspe.com</a><a class="inl text-white" href="tel:+358407746121" rel="nofollow">040 774 6121</a></div></div>
	</div>
</section>

</div></div>