<script>
	import '../lib/styles/global.scss';
</script>

<nav>
	<a href="/home">Home</a>
	<a href="/gallery">Gallery</a>
	<a href="/about">About</a>
</nav>

<slot />

<style lang="scss">
	nav {
		display: flex;
		align-content: space-around;
		gap: 100px;
		font-size: 1.2rem;
	}

	a {
		text-decoration: none;
		color: black;
	}
	a:hover {
		font-weight: bold;
		color: black;
	}
</style>
