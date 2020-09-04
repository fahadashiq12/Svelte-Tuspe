<script>
	import Logo from "./Logo.svelte"
	let active = false
	let nav = [
		{
			fi: {
				title: "Etusivu",
				url: ""
			},
			en: {
				title: "Home",
				url: "en/"
			}
		}, {
			fi: {
				title: "Kotisivut",
				url: "kotisivut-yritykselle"
			},
			en: {
				title: "Websites",
				url: "en/websites"
			}
		}, {
			fi: {
				title: "Verkkokaupat",
				url: "verkkokauppa-yritykselle"
			},
			en: {
				title: "E-commerce",
				url: "en/webstores"
			}
		}, {
			fi: {
				title: "Urheilusaitti",
				url: "sportti"
			},
			en: {
				title: "Sport platform",
				url: "en/sport"
			}
		}, {
			fi: {
				title: "Hakukoneoptimointi",
				url: "hakukoneoptimointi"
			},
			en: {
				title: "SEO",
				url: "en/seo"
			}
		}, {
			fi: {
				title: "Verkkotunnukset",
				url: "verkkotunnukset"
			},
			en: {
				title: "Domains",
				url: "en/domains"
			}
		}, {
			fi: {
				title: "Ylläpitopalvelut",
				url: "yllapito"
			},
			en: {
				title: "Web hotel",
				url: "en/hotel"
			}
		}, {
			fi: {
				title: "Referenssit",
				url: "referenssit"
			},
			en: {
				title: "References",
				url: "en/references"
			}
		}, {
			fi: {
				title: "Ota yhteyttä",
				url: "yhteys"
			},
			en: {
				title: "Contact us",
				url: "en/contact"
			}
		}
	]
</script>

<button id="toggler" class="fixed" class:open={active} class:bgw={!active} on:click={ () => active = !active} title="Avaa/sulje valikko">{#if !active}<svg viewBox="0 0 100 80" width="30" height="30"><title>Open navigation</title><rect width="100" height="20"></rect><rect y="30" width="100" height="20"></rect><rect y="60" width="100" height="20"></rect></svg>{:else}<svg width="30" height="30" id="ico"><title>Close navigation</title><path d="M0, -4 30, 35" stroke="#fff" stroke-width="6" /><path d="M0, 35 30, -4" stroke="#fff" stroke-width="6" /></svg>{/if}</button>
{#if active}
<nav id="menu" class="fixed">
	<div class="cell tc up">
		<ul>
			{#each nav as item}
				<li class="block"><a class="block" href={"/"+ item.fi.url} rel="prefetch" on:click={ () => active = false}>{item.fi.title}</a></li>
			{/each}
		</ul>
	</div>
</nav>
{/if}