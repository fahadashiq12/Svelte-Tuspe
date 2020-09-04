<script>
	import { metatags } from '@sveltech/routify'
	let sites = [
		{
			title: "NavyBlue Shop",
			url: "https://navyblue.fi/",
			img: "processwire-navyblue-2020",
			tech: "ProcessWire, Lemonsoft, PHP, SQL",
			fi: {
				desc: "Tyylikkäitä ja kovissakin olosuhteissa toimivia sporttisia vaatteita, asusteita ja jalkineita.",
				img: "Tyylikkäitä ja kestäviä sporttisia vaatteita, asusteita ja jalkineita."
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
			title: "Omamuutto",
			url: "https://omamuutto.fi/",
			img: "processwire-omamuutto-2020",
			fi: {
				desc: "Palvelu- ja omatoimimuutot sekä muuttotarvikkeet verkkokaupasta.",
				img: ""
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
			title: "SSTL Puhtausala ry",
			url: "https://puhtausala.fi/",
			img: "processwire-puhtausala-2019",
			fi: {
				desc: "Ajankohtaista tietoa, koulutuksia ja julkaisuja työsi ja ammatillisen kehittymisesi tueksi.",
				img: "Tietoa puhtausalasta ja sen toiminnasta"
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
		}, {
			title: "KoneJönnit",
			url: "https://www.konejonnit.fi/",
			img: "processwire-konejonnit-2020",
			fi: {
				desc: "Pienkoneet puutarhaan sekä moottorikulkuneuvot ja varusteet.",
				img: "Luotettava pienkonekauppaasi Itä-Suomessa!"
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Osuuskaupparock",
			url: "https://osuuskaupparock.fi/",
			img: "processwire-okr-2019",
			fi: {
				desc: "Jokavuotinen musiikkifestari Joensuussa.",
				img: "Mahtava kesätapahtuma Joensuussa"
			},
			en: {
				desc: "",
				img: ""
			}
		}, {
			title: "Tilitoimisto Helant",
			url: "https://helant.fi/",
			img: "processwire-helant-2018",
			fi: {
				desc: "Ammattitaitoinen ja joustava tili- ja toimistopalveluita tarjoava yritys.",
				img: "Jätä vaikeat kirjanpidot ja taloushallinnon kiemurat tilitoimiston hoidettavaksi"
			},
			en: {
				desc: "",
				img: ""
			}
		}
	]
	let desc = "Olemme toteuttaneet monipuolisesti erilaisia kotisivuja ja verkkokauppoja kaikenlaisille ja eri kokoisille toimijoille toiminimistä kansainvälisiin yrityksiin."
	let img = "https://timoanttila.com/images/gallery/2019-deli-yawns.jpg"
	let url = "https://tuspe.com/referenssit"
	metatags.title = "Referenssit | Tuspe Desgin"
	metatags.description = desc
	metatags.image = img
	metatags.url = url
	metatags.canonical = url
	metatags["twitter:card"] = "summary_large_image"
	metatags["twitter:description"] = desc
	metatags["twitter:image"] = img
	let ref = "/images/references/ref-"
</script>

<svelte:head>
	<link rel="stylesheet" href="/page.css">
</svelte:head>

<div id="page" class="refs">

<div class="container mxa small tc">
	<h1 class="effra title">Näistä töistämme olemme erityisen ylpeitä</h1>
	<p>{desc} Teemme suurimman osan töistämme alihankintana.</p>
	<p><a class="btn up" href="/yhteys">Tilaa ilmainen kartoitus</a></p>
</div>

<div id="references" class="container mxa fluid p3">
{#each sites as item}
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
</div></div>