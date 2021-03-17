<style>
    .Header {
        padding: 1em 0.5em 0 0.5em;
    }

    .Header-container {
        display: flex;
        flex-direction: column;
    }

    .Header-content {
        align-items: center;
    }

    .Header h1 {
        color: #f76b61;
        font-size: 28px;
        font-weight: 700;
        letter-spacing: 0.8px;
        cursor: pointer;
    }

    .Header h1 span {
        display: block;
        font-size: 13px;
        font-weight: 300;
        letter-spacing: normal;
        margin: 0.3em 0 0 0;
    }

    .Header ul {
        margin: 20px 0;
        padding: 10px 0;
        border-top: 1px solid #333;
        border-bottom: 1px solid #333;
        list-style: none;
    }

    .Header li {
        display: inline-block;
        margin: 0 0.5em 0 0;
    }

    .Header a {
        text-decoration: none;
        font-weight: 300;
        font-size: 14px;
    }

    .Header-social li a {
        font-size: 2em;
        color: #bdbdbd;
    }

    .Header-social li a:hover {
		color: rgba(10, 183, 206, 0.89);
    }
</style>

<header class="Header">
    <div class="Header-container">
        <div class="Header-content">
            <div class="Header-logo">
                <h1>
                    Jorge Carrión
                    <span>Backend developer</span>
                </h1>
            </div>
            <div class="Header-social">
                <ul>
                    <li>
                        <a class="fa fa-github-square" href="https://github.com/george28cs" target="_blank" rel="noreferrer">
                        </a>
                    </li>
                    <li>
                        <a class="fa fa-2x fa-linkedin-square" href="https://www.linkedin.com/in/jcarrion28/" target="_blank" rel="noreferrer">
                        </a>
                    </li>
                    <li>
                        <a class="fa fa-2x fa-youtube-square" href="https://www.youtube.com/channel/UCwuAYGYoB2PcGov6tO680xw" target="_blank" rel="noreferrer">
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</header>