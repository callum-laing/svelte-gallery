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

<style>
	h1 {
		text-align: center;
		border-bottom: 2px solid black;
		padding-bottom: 20px;
	}
	.img-grid {
		display: grid;
		grid-template-columns: repeat(3, 1fr);
		grid-template-rows: repeat(3, 1fr);
		grid-row-gap: 30px;
		place-items: center;
	}

	img {
		width: 600px;
	}
</style>
