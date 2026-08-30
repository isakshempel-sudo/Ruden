<!DOCTYPE html>
<html lang="da">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Ruden – VinduespudserApp</title>

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #071a2b, #0d4f70);
            color: white;
            min-height: 100vh;
        }

        header {
            padding: 25px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
        }

        .logo span {
            color: #48d7ff;
        }

        .hero {
            min-height: 75vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 40px 20px;
        }

        .content {
            max-width: 750px;
        }

        .window-icon {
            font-size: 80px;
            margin-bottom: 20px;
        }

        h1 {
            font-size: clamp(45px, 8vw, 80px);
            margin-bottom: 15px;
        }

        h1 span {
            color: #48d7ff;
        }

        .subtitle {
            font-size: 23px;
            color: #d7f5ff;
            margin-bottom: 15px;
        }

        .description {
            font-size: 17px;
            line-height: 1.6;
            color: #b9d9e5;
            margin-bottom: 35px;
        }

        .download {
            display: inline-block;
            background: #48d7ff;
            color: #062033;
            padding: 18px 35px;
            border-radius: 12px;
            text-decoration: none;
            font-size: 20px;
            font-weight: bold;
            transition: 0.2s;
            box-shadow: 0 8px 30px rgba(72, 215, 255, 0.25);
        }

        .download:hover {
            transform: translateY(-3px);
            background: #72e1ff;
            box-shadow: 0 12px 35px rgba(72, 215, 255, 0.4);
        }

        .windows {
            margin-top: 15px;
            color: #9fc3d0;
            font-size: 14px;
        }

        .features {
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
            padding: 30px 20px 70px;
        }

        .card {
            width: 220px;
            padding: 25px;
            background: rgba(255,255,255,0.08);
            border: 1px solid rgba(255,255,255,0.1);
            border-radius: 18px;
            text-align: center;
            backdrop-filter: blur(10px);
        }

        .card .icon {
            font-size: 35px;
            margin-bottom: 12px;
        }

        .card h2 {
            font-size: 18px;
            margin-bottom: 8px;
        }

        .card p {
            color: #b9d9e5;
            font-size: 14px;
            line-height: 1.5;
        }

        footer {
            text-align: center;
            padding: 25px;
            border-top: 1px solid rgba(255,255,255,0.1);
            color: #8eafba;
            font-size: 14px;
        }

        @media (max-width: 600px) {
            header {
                justify-content: center;
            }

            .hero {
                min-height: 65vh;
            }

            .subtitle {
                font-size: 19px;
            }
        }
    </style>
</head>

<body>

<header>
    <div class="logo">
        🪟 <span>Ruden</span>
    </div>
</header>

<section class="hero">

    <div class="content">

        <div class="window-icon">🪟</div>

        <h1>Ruden<span>.</span></h1>

        <div class="subtitle">
            VinduespudserApp
        </div>

        <p class="description">
            Et simpelt og praktisk program til vinduespudsere.
            Hold styr på kunder, opgaver og meget mere – samlet ét sted.
        </p>

        <a class="download" href="VinduespudserApp.exe" download>
            ⬇️ Download Ruden
        </a>

        <div class="windows">
            💻 Til Windows
        </div>

    </div>

</section>

<section class="features">

    <div class="card">
        <div class="icon">👥</div>
        <h2>Kunder</h2>
        <p>Hold styr på dine kunder og deres oplysninger.</p>
    </div>

    <div class="card">
        <div class="icon">📋</div>
        <h2>Opgaver</h2>
        <p>Få overblik over dine vinduespudsningsopgaver.</p>
    </div>

    <div class="card">
        <div class="icon">⚡</div>
        <h2>Nem at bruge</h2>
        <p>Et enkelt interface, der er hurtigt at komme i gang med.</p>
    </div>

</section>

<footer>
    © 2026 Ruden – VinduespudserApp
</footer>

</body>
</html>
