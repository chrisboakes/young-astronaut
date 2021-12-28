<style>
    .member__image-wrap {
        display: block;
        height: 0;
        padding-bottom: 100%;
        position: relative;
        width: 100%;
    }

    .member__image img {
        height: 100%;
		left: 0;
		position: absolute;
		top: 0;
		width: 100%;
    }

    .member__title, .member__description {
        font-family: 'Merriweather', serif;
        font-size: 1.2rem;
        font-weight: 300;
        margin-bottom: 0;
        margin-top: 20px;
        letter-spacing: initial;
        line-height: 1.5;
        text-align: left;
        text-transform: none;
    }

    .member__description {
        display: block;
        margin-top: 0;
    }

    .member__text {
        display: block;
        margin-bottom: 20px;
        position: relative;
    }

    .member__arrow {
        fill: #fff;
        height: 30px;
        position: absolute;
        right: 20px;
        top: 10px;
        width: 20px;
    }
</style>

<article>
    <header>
        <h2>Band Members</h2>
    </header>
    <ul class="members">
        <li class="member">
            <span class="member__image-wrap">
                <picture class="member__image">
                    <source srcset="/young-astronaut-chris-boakes.jpg"
                            media="(min-width: 768px)">
                    <source srcset="/young-astronaut-chris-boakes-square.jpg"
                            media="(min-width: 0px)">
                    <img src="/young-astronaut-chris-boakes.jpg"
                        alt="Chris Boakes"
                        width="300"
                        height="400"
                    />
                </picture>
            </span>

            <span class="member__text">
                <h5 class="member__title">Chris Boakes</h5>
                <span class="member__description">Vocals/guitar</span>
                <svg class="member__arrow">
                    <use xlink:href='#arrow'></use>
                </svg>
            </span>
        </li>
    </ul>
</article>
