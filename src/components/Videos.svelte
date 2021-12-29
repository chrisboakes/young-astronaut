<style>
    .video__wrapper {
        overflow: visible;
        margin-bottom: 20px;
        padding-top: 56.25%;
        position: relative;
    }

    iframe {
        border: 0;
        height: 100%;
        left: 0;
        position: absolute;
        top: 0;
        width: 100%;
    }

    .video__title-wrap {
        align-items: center;
        display: flex;
        flex-direction: row;
        margin-bottom: 10px;
        margin-top: 20px;
    }

    .video__title {
        font-family: 'Merriweather', serif;
        font-size: 1.2rem;
        font-weight: 300;
        letter-spacing: initial;
        line-height: 1.5;
        margin: 0;
        text-align: left;
        text-transform: none;
    }

    .video__icon {
        fill: #fff;
        height: 15px;
        margin-right: 10px;
        opacity: .5;
        width: 15px;
    }

    @media (min-width: 768px) {
        section {
            margin-top: 80px;
            grid-column: 2/12;
        }

        h2 {
            margin-bottom: 60px;
        }

        .video {
            align-items: center;
            display: flex;
            flex-direction: column;
            margin-bottom: 40px;
            justify-content: flex-end;
        }

        .video__wrapper {
            flex-shrink: 0;
            height: 349px;
            margin: 0;
            padding-top: 0;
            width: 620px;
        }

        .video__title-wrap {
            flex-direction: column;
            margin: 0 0 20px 0;
        }

        .video__title {
            font-size: 1.2rem;
        }

        .video__icon {
            height: 20px;
            margin-bottom: 5px;
            margin-right: 0;
            width: 20px;
        }
    }

    @media (min-width: 1024px) {
        .video {
            align-items: center;
            flex-direction: row;
            justify-content: flex-end;
        }

        .video__title-wrap {
            flex-grow: 1;
            margin: 0;
            padding: 0 60px;
            text-align: center;
        }

        .video__title {
            font-size: 2.3rem;
            opacity: .5;
            text-align: center;
        }

        .video:nth-child(even) {
            justify-content: flex-start;
        }

        .video:nth-child(even) .video__wrapper {
            order: 1;
        }

        .video:nth-child(even) .video__title-wrap {
            order: 2;
        }

        .video__icon {
            height: 25px;
            opacity: .2;
            width: 25px;
        }
    }
</style>

<section>
    <header>
	    <h2>Videos</h2>
    </header>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                The Chronicles Of Fall &amp; Glory
            </h4>
        </div>

        <div class="video__wrapper">        
            <iframe title="The Chronicles Of Fall &amp; Glory" width="620" height="349" src="https://www.youtube.com/embed/dBkLQu17VwM?modestbranding=1&autohide=1&showinfo=0&controls=0&rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                Chasing El Dorado
            </h4>
        </div>

        <div class="video__wrapper video__wrapper--thin">
            <iframe title="Chasing El Dorado" width="620" height="349" src="https://www.youtube.com/embed/1KVJnExCTy8?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                The Old Cool
            </h4>
        </div>

        <div class="video__wrapper video__wrapper--thin">
            <iframe title="The Old Cool" width="620" height="264" src="https://www.youtube.com/embed/lQabr1h4P-I?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                Chasing El Dorado (Live Session)
            </h4>
        </div>

        <div class="video__wrapper">
            <iframe title="Chasing El Dorado (Live Session)" width="620" height="264" src="https://www.youtube.com/embed/5ejd-4B6FLw?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                Hey Little Ghost
            </h4>
        </div>

        <div class="video__wrapper">
            <iframe title="Hey Little Ghost" width="620" height="264" src="https://www.youtube.com/embed/Bq4HC_RX8-o?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>

    <div class="video">
        <div class="video__title-wrap">
            <svg class="video__icon">
                <use xlink:href='#video'></use>
            </svg>
            <h4 class="video__title">
                Triumph
            </h4>
        </div>

        <div class="video__wrapper">
            <iframe title="Triumph" width="620" height="264" src="https://www.youtube.com/embed/FmWVhjfsLDM?rel=0" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </div>
</section>
