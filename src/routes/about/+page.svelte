<h1>About</h1>

<div class="about-grid">
	<img src="map.jpg" alt="" />
	<div class="about">
		<h2>Cal's Gallery</h2>

		<p>
			What is Lorem Ipsum? Lorem Ipsum is simply dummy text of the printing and typesetting
			industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when
			an unknown printer took a galley of type and scrambled it to make a type specimen book. It has
			survived not only five centuries, but also the leap into electronic typesetting, remaining
			essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets
			containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus
			PageMaker including versions of Lorem Ipsum.
		</p>
	</div>
</div>

<style lang="scss">
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

	.about {
		width: 75%;
	}
</style>
