<style>
	.recording {
		display: flex;
		flex-direction: column;
	}

	.recording__image {
		width: 100%;
	}

	.recording__title {
		text-align: left;
	}

	.recording__description {
		margin-bottom: 20px;
	}

	.recording__links {
		margin-bottom: 30px;
	}

	.recording__links svg {
		fill: #fff;
		margin-right: 10px;
		max-width: 20px;
		height: 20px;
	}

	.recording__links li {
		margin-bottom: 5px;
	}

	.recording__links li a {
		align-items: center;
		display: flex;
	}

	@media (min-width: 768px) {
		.recording {
			align-items: center;
			display: grid;
			margin-top: 50px;
			grid-column: span 12;
			grid-template-columns: repeat(12, 1fr);
		}

		.recording--reverse {
			margin-top: 20px;
		}

		.recording__image {
			grid-column: 2/6;
		}

		.recording__content {
			grid-column: 7/12;
		}

		.recording__title {
			margin-top: 0;
		}

		.recording__links {
			margin-bottom: 0;
		}

		.recording--reverse .recording__image {
			grid-column: 8/12;
			grid-row: 1;
		}

		.recording--reverse .recording__content {
			grid-column: 2/7;
			grid-row: 1;
			text-align: right;
		}

		.recording--reverse .recording__title {
			text-align: right;
		}

		.recording--reverse .recording__links li {
			display: inline-block;
		}
	}

	@media (min-width: 1024px) {
		.recording {
			margin-top: 80px;
		}

		.recording--reverse {
			margin-top: 30px;
		}

		.recording__image {
			grid-column: 2/5;
		}

		.recording__content {
			grid-column: 6/10;
		}

		.recording--reverse .recording__image {
			grid-column: 9/12;
		}

		.recording--reverse .recording__content {
			grid-column: 5/8;
		}
	}
</style>

<article class="recording">
	<img class="recording__image" src="/young-astronaut-hellions-single-cover.jpg" alt="Young Astronaut - Hellions single cover" />
	<div class="recording__content">
		<header>
			<h3 class="recording__title">Hellions</h3>
		</header>
		<p class="recording__description">The second single from our upcoming EP "Pirouette &amp; Fall"</p>
		<ul class="recording__links">
			<li>
				<a href="https://spoti.fi/3DoQCOZ" rel="noopener nofollow" aria-label="Listen to Hellions on Spotify">
					<svg>
						<use xlink:href='#shape-spotify'></use>
					</svg>
					<span>Listen on Spotify</span>
				</a>
			</li>
			<li>
				<a href="https://apple.co/3598kJm" rel="noopener nofollow" aria-label="Listen to Hellions on Apple Music">
					<svg>
						<use xlink:href='#shape-itunes'></use>
					</svg>
					<span>Listen on Apple Music</span>
				</a>
			</li>
		</ul>
	</div>
</article>

<article class="recording recording--reverse">
	<img class="recording__image" src="/young-astronaut-hope-single.jpg" alt="Young Astronaut - Hope single cover" />
	<div class="recording__content">
		<header>
			<h3 class="recording__title">Hope</h3>
		</header>
		<p class="recording__description">The first single from our upcoming EP "Pirouette &amp; Fall"</p>
		<ul class="recording__links">
			<li>
				<a href="https://spoti.fi/33cSZ9G" rel="noopener nofollow" aria-label="Listen to Hope on Spotify">
					<svg>
						<use xlink:href='#shape-spotify'></use>
					</svg>
					<span>Listen on Spotify</span>
				</a>
			</li>
			<li>
				<a href="https://apple.co/34sRy7V" rel="noopener nofollow" aria-label="Listen to Hope on Apple Music">
					<svg>
						<use xlink:href='#shape-itunes'></use>
					</svg>
					<span>Listen on Apple Music</span>
				</a>
			</li>
		</ul>
	</div>
</article>

<article class="recording">
	<img class="recording__image" src="/young-astronaut-a-gold-frontier.jpg" alt="Young Astronaut - A Gold Frontier album cover" />
	<div class="recording__content">
		<header>
			<h3 class="recording__title">A Gold Frontier</h3>
		</header>
		<p class="recording__description">Our sophomore release featuring singles "Chasing El Dorado", "The Old Cool" &amp; "The Chronicles of Fall & Glory"</p>
		<ul class="recording__links">
			<li>
				<a href="https://open.spotify.com/album/27t2gkNPkfcQqUa5kCLCnI" rel="noopener nofollow" aria-label="Listen to A Gold Frontier on Spotify">
					<svg>
						<use xlink:href='#shape-spotify'></use>
					</svg>
					<span>Listen on Spotify</span>
				</a>
			</li>
			<li>
				<a href="https://music.apple.com/gb/album/a-gold-frontier/1217721159" rel="noopener nofollow" aria-label="Listen to A Gold Frontier on Apple Music">
					<svg>
						<use xlink:href='#shape-itunes'></use>
					</svg>
					<span>Listen on Apple Music</span>
				</a>
			</li>
		</ul>
	</div>
</article>

<article class="recording recording--reverse">
	<img class="recording__image" src="/young-astronaut-fawn.jpg" alt="Young Astronaut - Fawn album cover" />
	<div class="recording__content">
		<header>
			<h3 class="recording__title">Fawn</h3>
		</header>
		<p class="recording__description">Our debut album featuring singles "Triumph" &amp; "Hey Little Ghost"</p>
		<ul class="recording__links">
			<li>
				<a href="https://open.spotify.com/album/38Bbfb5UWKJOVbudjIrirE" rel="noopener nofollow" aria-label="Listen to Fawn on Spotify">
					<svg>
						<use xlink:href='#shape-spotify'></use>
					</svg>
					<span>Listen on Spotify</span>
				</a>
			</li>
			<li>
				<a href="https://music.apple.com/jp/album/fawn/489444594" rel="noopener nofollow" aria-label="Listen to Fawn on Apple Music">
					<svg>
						<use xlink:href='#shape-itunes'></use>
					</svg>
					<span>Listen on Apple Music</span>
				</a>
			</li>
		</ul>
	</div>
</article>
