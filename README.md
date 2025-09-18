<html lang="sv">
<head>
    <meta charset="UTF-8">
    <title>Sayaara.se</title>
    <!-- Font Awesome CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
    <style>
        body {
            background-color: #c11314;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px 20px;
        }

        h1 {
            margin: 20px 0;
            font-size: 28px;
        }

        hr {
            border: none;
            border-top: 1px solid #fff;
            margin: 25px auto;
            width: 70%;
            opacity: 0.4;
        }

        a {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 12px;
            margin: 15px auto;
            padding: 15px 25px;
            width: 240px;
            color: #fff;
            text-decoration: none;
            border-radius: 12px;
            font-size: 18px;
            font-weight: bold;
            box-shadow: 0 4px 12px rgba(0,0,0,0.25);
            transition: transform 0.2s, opacity 0.3s;
        }

        a:hover {
            transform: translateY(-4px);
            opacity: 0.9;
        }

        /* Instagram-knapp */
        .instagram {
            background: linear-gradient(45deg, #feda75, #fa7e1e, #d62976, #962fbf, #4f5bd5);
        }

        /* TikTok-knapp */
        .tiktok {
            background: #000;
        }

        /* Ikoner */
        .fa-instagram {
            color: #fff;
        }

        .fa-tiktok {
            color: #25F4EE; /* TikTok turkos */
            text-shadow: 1px 1px #FE2C55; /* röd/rosa glow */
        }

        /* Responsivitet */
        @media (max-width: 500px) {
            a {
                width: 90%;
                font-size: 16px;
                padding: 12px 20px;
            }
        }
    </style>
</head>
<body>
    <h1>Sayaara</h1>
    <hr>
    <h1>Våra sociala medier 👇</h1>

    <a href="https://www.instagram.com/sayaara.se" target="_blank" class="instagram">
        <i class="fab fa-instagram"></i> Instagram
    </a>

    <a href="https://www.tiktok.com/@sayaara.se" target="_blank" class="tiktok">
        <i class="fab fa-tiktok"></i> TikTok
    </a>
</body>
</html>
