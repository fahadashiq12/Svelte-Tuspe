<script>
	let making = [
		{
			id: 1,
			title: "Suunnitellaan yhdessä",
			info: "Hyvin suunniteltu on alku kohti täydellistä lopputulosta. Määritellään tarvittavat ainekset kotisivuillesi, pyöritellään ne yhteen ja lähdetään toteuttamaan seuraavaa vaihetta kohti yhtenäistä kokonaisuutta. Kotisivusi ovat yrityksesi peliväline ja ne tarvitsevat erilaisia elementtejä: vetävän ulkoasun ja täsmällisen sisällön, aivan kuten pallokin tarvitsee väriä. Tekniikkaa unohtamatta."
		},{
			id: 2,
			title: "Kehitetään yhdessä",
			info: "Ei yksivärinen, vaan eläväinen ja näkyvä! Kun kaikki tarvittava on määritelty, kasataan kotisivujesi suunnitelma kuntoon. Lopputuloksena saat tarjouksen & suunnitelman sivustostasi, mitä kaikkea se sisältää ja miten ylläpito jatkossa hoituu."
		},{
			id: 3,
			title: "Valmiina kentälle",
			info: "Tässä vaiheessa peliväline on kunnossa ja on aika lähteä rakentamaan peliä. Eli toteutetaan kotisivusi sinulle suunnitelman mukaan valmiiksi ja kohta oletkin jo  valmiina pelikentälle. Kun suunnitelma on rautainen, pelaat yrityksesi suoraan potentiaalisten asiakkaiden maaliin ja teet tulosta!"
		}
	]
</script>

<section id="how" class="p3 bgLight">
	<div class="container mxa small tc"><h2 class="effra sub1 m3">Mites ne asiat<br>meillä hoidetaan?</h2></div>
	<div class="container mxa wide">
		<div class="howGrid grid">
		{#each making as item}
			<div class="how rel">
				<div class="howNum abs mont">{item.id}</div>
				<div><h3 class="effra sub2">{item.title}</h3>{@html item.info}</div>
			</div>
		{/each}
		</div>
	</div>
</section>