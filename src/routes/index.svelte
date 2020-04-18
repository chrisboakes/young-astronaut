<style>
	h2 {
		font-family: 'Courier New', Courier, monospace;
		font-size: 24px;
		letter-spacing: 2px;
		margin-bottom: 20px;
		text-align: center;
		text-transform: uppercase;
	}

	h3 {
		color: #fff;
	}

	p {
		margin-bottom: 5px;
	}

	@media (min-width: 768px) {
		.recordings {
			display: flex;
			justify-content: center;
			margin: 20px 0 0 0;
		}
	}

	article {
		padding-bottom: 20px;
		margin: 0 auto;
		width: 300px;
	}

	@media (min-width: 768px) {
		article {
			margin: 0;
		}

		article:first-child {
			margin-right: 20px;
		}
	}

	article svg {
		fill: #fff;
		margin-right: 10px;
		max-width: 20px;
		height: 20px;
	}

	article li {
		margin-bottom: 5px;
	}

	article li a {
		align-items: center;
		display: flex;
	}
</style>

<svelte:head>
	<title>Young Astronaut Band</title>
	<meta name="description" content="Music, news, videos and merchandise from British indie band Young Astronaut.">
</svelte:head>


<div class="recordings">
	<article>
		<img src="/young-astronaut-a-gold-frontier.jpg" alt="Young Astronaut - A Gold Frontier album cover" />
		<header>
			<h3>A Gold Frontier</h3>
			<p>Listen on:</p>
			<ul>
				<li>
					<a href="https://open.spotify.com/album/27t2gkNPkfcQqUa5kCLCnI" rel="noopener nofollow" aria-label="Listen to A Gold Frontier on Spotify">
						<svg>
							<use xlink:href='#shape-spotify'></use>
						</svg>
						<span>Spotify</span>
					</a>
				</li>
				<li>
					<a href="https://music.apple.com/gb/album/a-gold-frontier/1217721159" rel="noopener nofollow" aria-label="Listen to A Gold Frontier on Spotify">
						<svg>
							<use xlink:href='#shape-itunes'></use>
						</svg>
						<span>Apple Music</span>
					</a>
				</li>
			</ul>
		</header>
	</article>

	<article>
		<img src="/young-astronaut-fawn.jpg" alt="Young Astronaut - Fawn album cover" />
		<header>
			<h3>Fawn</h3>
			<p>Listen on:</p>
			<ul>
				<li>
					<a href="https://open.spotify.com/album/38Bbfb5UWKJOVbudjIrirE" rel="noopener nofollow" aria-label="Listen to Fawn on Spotify">
						<svg>
							<use xlink:href='#shape-spotify'></use>
						</svg>
						<span>Spotify</span>
					</a>
				</li>
				<li>
					<a href="https://music.apple.com/jp/album/fawn/489444594" rel="noopener nofollow" aria-label="Listen to Fawn on Spotify">
						<svg>
							<use xlink:href='#shape-itunes'></use>
						</svg>
						<span>Apple Music</span>
					</a>
				</li>
			</ul>
		</header>
	</article>
</div>

<section>
	<h2>Music Videos</h2>
</section>