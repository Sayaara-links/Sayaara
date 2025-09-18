<!DOCTYPE html>
<html lang="sv">
<head>
  <meta charset="UTF-8">
  <title>Sayaara.se</title>
  <!-- Google Fonts Montserrat -->
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      background: linear-gradient(135deg, #c11314, #e63946);
      color: #fff;
      font-family: 'Montserrat', sans-serif;
      text-align: center;
      padding: 50px;
      margin: 0;
    }
    h1 {
      margin: 40px 0 20px;
      font-size: 2rem;
    }
    .link {
      display: flex;
      align-items: center;
      justify-content: center;
      margin: 20px auto;
      padding: 15px 30px;
      width: 250px;
      background-color: #fff;
      color: #000;
      text-decoration: none;
      border-radius: 12px;
      font-size: 18px;
      font-weight: 600;
      box-shadow: 0 6px 15px rgba(0,0,0,0.3);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .link:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 20px rgba(0,0,0,0.4);
    }
    .link i {
      margin-right: 10px;
      font-size: 20px;
    }
    .instagram {
      background: linear-gradient(45deg, #feda75, #d62976, #962fbf, #4f5bd5);
      color: #fff;
    }
    .tiktok {
      background: #000;
      color: #fff;
    }
    hr {
      margin: 30px auto;
      width: 80%;
      border: none;
      border-top: 2px solid rgba(255,255,255,0.4);
    }
    .top-link {
      display: inline-block;
      margin-top: 10px;
      padding: 12px 25px;
      background-color: #c11314;
      color: #fff;
      text-decoration: none;
      font-weight: bold;
      border-radius: 10px;
      box-shadow: 0 5px 15px rgba(0,0,0,0.3);
      transition: transform 0.2s, box-shadow 0.2s;
    }
    .top-link:hover {
      transform: translateY(-3px);
      box-shadow: 0 8px 18px rgba(0,0,0,0.4);
    }
  </style>
  <!-- Font Awesome för ikoner -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>
  <!-- Länk högst upp -->
  <a href="https://www.sayaara.se" target="_blank" class="top-link">Sayaara</a>

  <h1>Våra sociala medier 👇</h1>
  <hr>

  <a href="https://www.instagram.com/sayaara.se?igsh=MXVqZDhsazlkNWk1dA%3D%3D&utm_source=qr" 
     target="_blank" class="link instagram">
    <i class="fab fa-instagram"></i> Instagram
  </a>

  <a href="https://www.tiktok.com/@sayaara.se?_t=ZN-8zoSgZ8UbzC&_r=1" 
     target="_blank" class="link tiktok">
    <i class="fab fa-tiktok"></i> TikTok
  </a>
</body>
</html>
