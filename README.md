<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Zubair Website</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Arial, sans-serif;
      background: #111;
      color: white;
      text-align: center;
    }

    header {
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 30px 20px;
      background: linear-gradient(135deg, #111, #333, #111);
    }

    h1 {
      font-size: 45px;
      margin-bottom: 15px;
      animation: fadeIn 1.5s ease;
    }

    p {
      font-size: 20px;
      color: #ccc;
      margin-bottom: 25px;
    }

    img {
      width: 230px;
      max-width: 90%;
      border-radius: 25px;
      margin: 20px 0;
      box-shadow: 0 10px 30px #000;
    }

    .btn {
      display: inline-block;
      padding: 14px 28px;
      background: white;
      color: #111;
      text-decoration: none;
      border-radius: 30px;
      font-weight: bold;
      transition: 0.3s;
    }

    .btn:hover {
      transform: scale(1.08);
    }

    section {
      padding: 60px 20px;
    }

    h2 {
      font-size: 32px;
      margin-bottom: 15px;
    }

    @keyframes fadeIn {
      from {
        opacity: 0;
        transform: translateY(30px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 34px;
      }
    }
  </style>
</head>

<body>

  <header>
    <h1>Welcome to Zubair Website 👋</h1>

    <p>My personal website 🚀</p>

    <img src="photo.jpg" alt="Zubair">

    <a class="btn" href="#about">About Me</a>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>Welcome to my website. Thanks for visiting! ❤️</p>
  </section>

</body>
</html>
