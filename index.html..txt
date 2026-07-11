<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kenichi Nakayama | Digital Artist</title>
    <meta name="description" content="Tokyo-based digital artist Kenichi Nakayama - 世紀末少学生X年X組シリーズ">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Helvetica Neue', Arial, sans-serif;
            background-color: #0f0f0f;
            color: #e0e0e0;
            line-height: 1.7;
            scroll-behavior: smooth;
        }
        header {
            padding: 1.5rem 5%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            border-bottom: 1px solid #333;
            position: sticky;
            top: 0;
            background-color: rgba(15,15,15,0.95);
            backdrop-filter: blur(10px);
            z-index: 100;
        }
        .logo {
            font-size: 1.4rem;
            font-weight: 600;
            letter-spacing: 0.05em;
        }
        nav a {
            color: #e0e0e0;
            text-decoration: none;
            margin-left: 2rem;
            font-weight: 500;
            transition: color 0.3s;
        }
        nav a:hover {
            color: #fff;
        }

        .hero {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            background: linear-gradient(rgba(0,0,0,0.65), rgba(0,0,0,0.75)), 
                        url('https://via.placeholder.com/1920x1080/111/ddd?text=KENICHI+NAKAYAMA') center/cover no-repeat;
            position: relative;
        }
        .hero-content h1 {
            font-size: clamp(3rem, 8vw, 6rem);
            margin-bottom: 1rem;
            letter-spacing: 0.15em;
            font-weight: 700;
        }
        .hero-content p {
            font-size: 1.35rem;
            opacity: 0.95;
            max-width: 600px;
            margin: 0 auto;
        }

        section {
            padding: 7rem 5%;
        }
        h2 {
            text-align: center;
            margin-bottom: 3.5rem;
            font-size: 2.2rem;
            letter-spacing: 0.08em;
        }

        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
            gap: 2.5rem;
        }
        .portfolio-item {
            position: relative;
            overflow: hidden;
            border-radius: 4px;
        }
        .portfolio-item img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s ease;
        }
        .portfolio-item:hover img {
            transform: scale(1.08);
        }
        .portfolio-item h3 {
            margin-top: 1.2rem;
            text-align: center;
            font-size: 1.05rem;
            line-height: 1.5;
        }

        .welcome {
            text-align: center;
            max-width: 800px;
            margin: 0 auto;
            font-size: 1.25rem;
        }

        footer {
            text-align: center;
            padding: 4rem 5%;
            border-top: 1px solid #333;
            font-size: 0.95rem;
            opacity: 0.6;
        }

        /* モバイル調整 */
        @media (max-width: 768px) {
            nav a { margin-left: 1rem; font-size: 0.95rem; }
            .hero-content h1 { font-size: 3.5rem; }
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Kenichi Nakayama</div>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#portfolio">Portfolio</a>
            <a href="#store">Store</a>
        </nav>
    </header>

    <!-- Hero -->
    <section id="home" class="hero">
        <div class="hero-content">
            <h1>KENICHI NAKAYAMA</h1>
            <p>Digital Artist / Based in Tokyo</p>
        </div>
    </section>

    <!-- Welcome -->
    <section>
        <div class="welcome">
            <h2>Welcome to my world</h2>
            <p>
                誰でも手に取れる道具と素材、純粋に色を塗るという行為から塗らないという行為まで自分の芸術の確立を目指しています<br>
                その一つの表現が<em>「世紀末少学生X年X組」</em>シリーズです。
            </p>
        </div>
    </section>

    <!-- About -->
    <section id="about">
        <h2>About Me</h2>
        <p style="text-align:center; max-width: 720px; margin: 0 auto; font-size: 1.2rem;">
            私はこれまでいくつかの名前で創作活動を続けてきました。<br>
            KenAzumA or xxKen→ Kenichi Nakayama<br><br>
            
            東京を拠点に、<strong>子どもの無垢さと心</strong>をテーマに制作しています。<br>
            デジタルとアナログの融合によって、子どもの持つ純粋さ・驚き・遊び心を表現します。
        </p>
    </section>

    <!-- Portfolio -->
    <section id="portfolio">
        <h2>Portfolio</h2>
        <div class="portfolio-grid">
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400/222/fff?text=2018+KenAzumA" alt="2018 KenAzumA Exhibition">
                <h3>Nov, 2018.<br>
                    KenAzumA展 世紀末少学生X年X組<br>
                    -個性豊かなこどもたちとたのしいよかん-<br>
                    Hilton Tokyo, Hiltopia ART-SQUARE
                </h3>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400/222/fff?text=2020+Sato" alt="2020 Sato's Exhibition">
                <h3>Dec, 2020.<br>
                    Sato's posthumous work exhibition.<br>
                    新生少女誕生 - Sato works & Ken works -<br>
                    Gallery Ginza
                </h3>
            </div>
            <div class="portfolio-item">
                <img src="https://via.placeholder.com/600x400/222/fff?text=2022+Focus" alt="2022 Kenichi Nakayama Exhibition">
                <h3>Dec, 2022.<br>
                    ✴︎Focus on yourself.<br>
                    -small garden and 19Art-<br>
                    Fureai Park Hyakunincho, Tokyo
                </h3>
            </div>
        </div>
    </section>

    <!-- Store -->
    <section id="store">
        <h2>Store</h2>
        <p style="text-align:center; font-size: 1.3rem;">Coming soon...</p>
    </section>

    <footer>
        © 2026 Kenichi Nakayama. All Rights Reserved.
    </footer>
</body>
</html>



