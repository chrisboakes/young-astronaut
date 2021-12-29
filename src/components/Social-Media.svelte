<style>
    article {
        margin-top: 60px;
        margin-bottom: 100px;
    }

    .social__item {
        margin-bottom: 5px;
    }

    .social__item-link {
        align-items: center;
        display: flex;
        flex-direction: row;
    }

    .social__item-link:hover .social__item-text {
        text-decoration: underline;
    }

    .social__svg {
		fill: #fff;
        margin-right: 10px;
		max-width: 20px;
        opacity: .3;
		height: 20px;
	}

	.social__item-link:hover .social__svg {
		fill: #fff;
        opacity: 1;
	}

    .social__items-wrap {
        align-items: center;
        display: flex;
        flex-direction: column;
    }

    @media (min-width: 768px) {
        article {
            margin-top: 80px;
            grid-column: 2/12;
        }
    }

    @media (min-width: 1280px) {
        .social__items-wrap {
            flex-wrap: wrap;
            margin-top: 40px;
            flex-direction: row;
            justify-content: space-between;
        }
    }
</style>

<article>
    <header>
        <h2>Social Media</h2>
    </header>

    <ul class="social__items-wrap">
        <li class="social__item">
            <a href="https://www.facebook.com/youngastronautband" class="social__item-link" rel="noopener nofollow" aria-label="Visit the Young Astronaut Facebook page">
                <svg class="social__svg">
                    <use xlink:href='#shape-facebook'></use>
                </svg>
                <span class="social__item-text">
                    Facebook
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="https://twitter.com/yastronaut" class="social__item-link" rel="noopener nofollow" aria-label="Visit the Young Astronaut Twitter page">
                <svg class="social__svg">
                    <use xlink:href='#shape-twitter'></use>
                </svg>
                <span class="social__item-text">
                    Twitter
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="http://instagram.com/youngastronautband/" class="social__item-link" rel="noopener nofollow" aria-label="Visit the Young Astronaut Instagram page">
                <svg class="social__svg">
                    <use xlink:href='#shape-instagram'></use>
                </svg>
                <span class="social__item-text">
                    Instagram
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="https://www.youtube.com/user/youngastronautband" class="social__item-link" rel="noopener nofollow" aria-label="Visit the Young Astronaut YouTube page">
                <svg class="social__svg">
                    <use xlink:href='#shape-youtube'></use>
                </svg>
                <span class="social__item-text">
                    YouTube
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="https://soundcloud.com/young-astronaut/" class="social__item-link" rel="noopener nofollow" aria-label="Listen to Young Astronaut on Soundcloud">
                <svg class="social__svg">
                    <use xlink:href='#shape-soundcloud'></use>
                </svg>
                <span class="social__item-text">
                    Soundcloud
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="http://open.spotify.com/artist/5mWvB7w84pPL7h2xXWuxaQ" class="social__item-link" rel="noopener nofollow" aria-label="Listen to Young Astronaut on Spotify">
                <svg class="social__svg">
                    <use xlink:href='#shape-spotify'></use>
                </svg>
                <span class="social__item-text">
                    Spotify
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="https://itunes.apple.com/gb/artist/young-astronaut/id489444596" class="social__item-link" rel="noopener nofollow" aria-label="Listen to Young Astronaut on Apple Music">
                <svg class="social__svg">
                    <use xlink:href='#shape-itunes'></use>
                </svg>
                <span class="social__item-text">
                    Apple Music
                </span>
            </a>
        </li>
        <li class="social__item">
            <a href="mailto:youngastronautband@gmail.com" class="social__item-link" rel="noopener nofollow" aria-label="Email Young Astronaut">
                <svg class="social__svg">
                    <use xlink:href='#shape-email'></use>
                </svg>
                <span class="social__item-text">
                    youngastronautband@gmail.com
                </span>
            </a>
        </li>
    </ul>
</article>
