<h1>Gallery</h1>

<div class="img-grid">
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
	<img src="laptop-img.jpg" alt="" />
</div>

<style lang="scss">
	.img-grid {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		grid-template-rows: repeat(3, 1fr);
		grid-row-gap: 30px;
		place-items: center;
		padding-bottom: 20px;
	}

	img {
		width: 600px;
		border-radius: 10px;
		box-shadow: 2px 2px 2px 2px;
	}
</style>
