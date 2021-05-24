<script>

function rättknapp() {
	document.getElementById("knapp1").style.backgroundColor = "green"
}
function felknapp() {
	document.getElementById("knapp2").style.backgroundColor = "röd"
}
function felknapp1() {
	document.getElementById("knapp3").style.backgroundColor = "röd"
}
</script>

<main>

	
	<h1>Vem är blixten mcqueen</h1>
	
	<button on:click={rättknapp} id="knapp1"></button>
	<button on:click={felknapp} id="knapp2"></button>
	<button on:click={felknapp} id="knapp3"></button>

	

	

	



</main>

<style>
	:global(body) {
		background-image: url("https://images.hdqwalls.com/wallpapers/lightning-mcqueen-cars-3-hd-er.jpg");
		background-repeat: no-repeat;
		background-size: auto;
	}
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}
	#knapp1 {
		background-image: url("https://upload.wikimedia.org/wikipedia/en/8/82/Lightning_McQueen.png");
		width: 300px;
		height: 150px;
		background-repeat: no-repeat;
		background-size: auto;
	}
	#knapp2 {
background-image: url("https://i.dlpng.com/static/png/6827752_preview.png");
		width: 300px;
		height: 150px;
		background-repeat: no-repeat;
		background-size: auto;
	}
	#knapp3 {
background-image: url("https://img.webme.com/pic/p/pixarcars/cars---the-king-01.jpg");
		width: 300px;
		height: 150px;
		background-repeat: no-repeat;
		background-size: auto;
	}

	
	
		

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>