<script>
	import Socials from '../components/Socials.svelte';
</script>

<style>
	.header-wrapper {
		height: 350px;
		margin-bottom: 80px;
		position: relative;
		width: 100%;
	}

	header {
		display: block;
		text-align: center;
		width: 100%;
	}

	h1 {
		color: var(--light);
		font-size: 1rem;
		letter-spacing: .5rem;
		line-height: 1.2;
		margin: 0;
	}

	.header-image {
		height: 350px;
		left: 0;
		position: absolute;
		top: 0;
		width: 100%;
		z-index: 0;
	}

	.header-image img {
		object-fit: cover;
		height: 350px;
		width: 100%;
	}

	.header-content {
		padding-top: 40px;
		position: relative;
		z-index: 1;
	}

	.socials {
		padding-top: 315px;
	}

	@media (min-width: 768px) {
		.header-wrapper {
			grid-column: span 12;
			height: 500px;
			margin-bottom: 0;
		}

		.header-content {
			padding-left: 40px;
			padding-right: 40px;
			width: calc(100% - 40px);
		}

		.socials {
			grid-column: 7/12;
			grid-row: 1;
			padding-top: 0;
		}

		header {
			grid-column: 1/12;
			grid-row: 1;
			text-align: left;
		}

		h1 {
			font-size: 1.5rem;
			text-align: left;
		}

		.header-image {
			height: 500px;
		}

		.header-image img {
			height: 500px;
		}
	}

	@media (min-width: 1024px) {
		.header-content {
			padding-left: 0;
			padding-right: 0;
		}

		header {
			grid-column: 2/12;
		}

		h1 {
			font-size: 1.9rem;
		}

		.socials {
			grid-column: 7/12;
		}
	}
</style>

<div class="header-wrapper">
	<div class="grid header-content">
		<header>
			<h1>Young Astronaut</h1>
		</header>

		<div class="socials">
			<Socials />
		</div>
	</div>

	<picture class="header-image">
		<source srcset="/young-astronaut-band.jpg"
				media="(min-width: 768px)">
		<source srcset="/young-astronaut-band-mobile.jpg"
				media="(min-width: 0px)">
		<img src="/young-astronaut-band.jpg"
			alt="Young Astronaut Band"
			width="1200"
			height="500"
		/>
	</picture>
</div>
