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
        opacity: .3;
        position: absolute;
        right: 20px;
        top: 10px;
        width: 20px;
    }

    @media (min-width: 768px) {
        article {
            grid-column: 2/12;
            margin-top: 40px;
        }

        h2 {
            margin-bottom: 40px;
        }

        .members {
            display: flex;
            flex-direction: row;
        }

        .member {
            display: flex;
            flex-direction: column;
            width: 25%;
        }

        .member__text {
            padding-left: 20px;
        }

        .member:nth-child(1) .member__text {
            padding-left: 0;
        }

        .member:nth-child(even) {
            margin-top: 80px;
        }

        .member:nth-child(even) .member__text {
            order: 1;
        }

        .member:nth-child(even) .member__image-wrap {
            order: 2;
        }

        .member__image-wrap {
            padding-bottom: 133%;
        }

        .member__title, .member__description {
            font-size: 1rem;
        }

        .member__arrow {
            height: 23px;
            top: 32px;
            width: 15px;
        }

        .member:nth-child(even) .member__arrow {
            transform: rotate(180deg);
        }
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
        <li class="member">
            <span class="member__image-wrap">
                <picture class="member__image">
                    <source srcset="/young-astronaut-pete-boakes.jpg"
                            media="(min-width: 768px)">
                    <source srcset="/young-astronaut-pete-boakes-square.jpg"
                            media="(min-width: 0px)">
                    <img src="/young-astronaut-pete-boakes.jpg"
                        alt="Pete Boakes"
                        width="300"
                        height="400"
                    />
                </picture>
            </span>

            <span class="member__text">
                <h5 class="member__title">Pete Boakes</h5>
                <span class="member__description">Keys/guitar</span>
                <svg class="member__arrow">
                    <use xlink:href='#arrow'></use>
                </svg>
            </span>
        </li>
        <li class="member">
            <span class="member__image-wrap">
                <picture class="member__image">
                    <source srcset="/young-astronaut-paul-meeson.jpg"
                            media="(min-width: 768px)">
                    <source srcset="/young-astronaut-paul-meeson-square.jpg"
                            media="(min-width: 0px)">
                    <img src="/young-astronaut-paul-meeson.jpg"
                        alt="Paul Meeson"
                        width="300"
                        height="400"
                    />
                </picture>
            </span>

            <span class="member__text">
                <h5 class="member__title">Paul Meeson</h5>
                <span class="member__description">Bass</span>
                <svg class="member__arrow">
                    <use xlink:href='#arrow'></use>
                </svg>
            </span>
        </li>
        <li class="member">
            <span class="member__image-wrap">
                <picture class="member__image">
                    <source srcset="/young-astronaut-alex-esp.jpg"
                            media="(min-width: 768px)">
                    <source srcset="/young-astronaut-alex-esp-square.jpg"
                            media="(min-width: 0px)">
                    <img src="/young-astronaut-alex-esp.jpg"
                        alt="Alex Esp"
                        width="300"
                        height="400"
                    />
                </picture>
            </span>

            <span class="member__text">
                <h5 class="member__title">Alex Esp</h5>
                <span class="member__description">Drums</span>
                <svg class="member__arrow">
                    <use xlink:href='#arrow'></use>
                </svg>
            </span>
        </li>
    </ul>
</article>
