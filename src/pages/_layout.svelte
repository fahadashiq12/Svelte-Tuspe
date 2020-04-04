<script>
	import Footer from "../components/Footer.svelte"
	import { scrollto } from "svelte-scrollto"
	let openMenu
</script>
<a id="logo" href="/" rel="home" hreflang="fi">
	<picture>
		<source srcset="/images/tuspe-logo.webp" type="images/webp">
		<source srcset="/images/tuspe-logo.png" type="images/webp">
		<img src="/images/tuspe-logo.png" alt="Tuspe Design Oy - Se parempi digitoimisto">
	</picture>
</a>
<button id="menu-toggler" class:open={openMenu} on:click={ () => openMenu = !openMenu} title="Open/close navigation">
	{#if !openMenu}
	<svg viewBox="0 0 100 80" width="40" height="40">
		<rect width="100" height="20"></rect>
		<rect y="30" width="100" height="20"></rect>
		<rect y="60" width="100" height="20"></rect>
	</svg>
	{:else}
	<svg width="30" height="30">
    	<path d="M0, -4 30, 35" stroke="#000" stroke-width="6" />
    	<path d="M0, 35 30, -4" stroke="#000" stroke-width="6" />
	</svg>
	{/if}
	<span class="hidden">Menu</span>
</button>
{#if openMenu}
<nav id="menu">
	<div class="cell tc">
		<ul>
			<li><a href="/" rel="home">Etusivu</a></li>
			<li><a use:scrollto={'#services'} on:click={ () => openMenu = !openMenu} href="#services" title="Verkkosivujen suunnittelu ja toteutus">Palvelut</a></li>
			<li><a use:scrollto={'#latest'} on:click={ () => openMenu = !openMenu} href="/#latest" title="Tutustu viimeisimpiin töihimme">Referenssit</a></li>
			<li><a use:scrollto={'#partner'} on:click={ () => openMenu = !openMenu} href="/#partner" title="Haemme uusia yhteistyökumppaneita">Kumppaniksi?</a></li>
			<li><a use:scrollto={'#internship'} on:click={ () => openMenu = !openMenu} href="/#internship" title="Kaipaatko työharjoittelupaikkaa">Harjoittelijaksi?</a></li>
			<li><a use:scrollto={'#contact'} on:click={ () => openMenu = !openMenu} href="/#contact" title="Yhteystiedot">Yhteystiedot</a></li>
		</ul>
	</div>
</nav>
{/if}
<div id="wrap">
	<main><slot /></main>
	<Footer/>
</div>