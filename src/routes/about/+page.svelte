<h1>About</h1>

<div class="about-grid">
	<img src="map.jpg" alt="" />
	<p class="about-info">Text with details about</p>
</div>

<style>
	.about-grid {
		display: grid;
		grid-template-columns: 1fr 1fr;
		grid-template-rows: 1fr;
		place-items: center;
	}

	.about-info {
		background-color: lightgrey;
	}

	img {
		border-radius: 10px;
	}
</style>
