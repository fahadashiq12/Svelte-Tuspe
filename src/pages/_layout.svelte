<script>
	import Logo from "../components/Logo.svelte"
	import Footer from "../components/Footer.svelte"
	let openMenu
</script>
<Logo />

<div id="wrap">

	<main><slot /></main>

	<footer class="tw tc">
		<div id="contact" class="mx w9">
			<div class="row">
				<div class="col">
					<div class="cell">
						<h4>Uusi projekti?</h4>
						Valmiina palvelemaan
					</div>
				</div>
				<div class="col">
					<div class="cell">
						Tuspe Design Oy<br>3129423-2
					</div>
				</div>
				<div class="col">
					<div class="cell">
						<a class="tw" href="tel:+358407746121" rel="nofollow">040 774 6121</a>
						<a class="tw" href="mailto:myynti@tuspe.com" rel="nofollow">myynti@tuspe.com</a>
					</div>
				</div>
				<div class="col">
					<div class="cell">
						Särkäntie 6<br>
						27170 Eurajoki
					</div>
				</div>
			</div>
		</div>
		<Footer/>
	</footer>

</div>