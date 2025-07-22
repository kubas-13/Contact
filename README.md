<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <meta http-equiv="X-UA-Compatible" content="ie=edge"/>
  <title>Mantas Krutulis Portfolio</title>
  <style>
    body {
      font-family: sans-serif;
      background: #0B132B;
      color: #fff;
      margin: 0;
      padding: 0;
    }

    nav {
      background: #1C2541;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
    }

    .nav-left a.name {
      color: #ffffff;
      font-family: 'Times New Roman', Times, serif;
      font-size: 32px;
      text-decoration: none;
    }

    .nav-left h2 {
      margin: 0;
      font-size: 18px;
      color: #ffffff;
    }

    .nav-right {
      display: flex;
      gap: 1.5rem;
    }

    .nav-right a {
      color: #ffffff;
      font-size: 18px;
      text-decoration: none;
    }

    .nav-right a:hover {
      opacity: 0.7;
    }

    .about-section {
      text-align: center;
      padding: 4rem 2rem 2rem;
    }

    .about-section h2 {
      font-size: 42px;
      color: #5BC0BE;
      margin-bottom: 0.5rem;
    }

    .about-section p {
      font-size: 20px;
      color: #3A506B;
      margin-bottom: 2rem;
    }

    .social-icons {
      display: flex;
      justify-content: center;
      gap: 2.5rem;
      flex-wrap: wrap;
      margin-bottom: 4rem;
    }

    .social-icons img {
      width: 65px;
      height: 65px;
       border-radius: 50%;
      transition: transform 0.3s ease;
    }

    .social-icons img:hover {
      transform: scale(1.1);
      opacity: 0.8;
    }

    @media (max-width: 768px) {
      nav {
        flex-direction: column;
        align-items: flex-start;
      }

      .nav-right {
        margin-top: 1rem;
        flex-direction: column;
        gap: 0.5rem;
      }
    }
  </style>
</head>

<body>

  <nav>
    <div class="nav-left">
      <a class="name" href="PortFolio.html"><strong>Mantas Krutulis</strong></a>
      <h2>Game Developer</h2>
    </div>
    <div class="nav-right">
  <a href="https://kubas-13.github.io/Portfolio/">HOME</a>
      <a href="https://kubas-13.github.io/Demo/">DEMOS</a>
      <a href="https://kubas-13.github.io/Games/">GAMES</a>
      <a href="https://kubas-13.github.io/Contact/">CONTACT</a>
    </div>
  </nav>

  <section class="about-section">
    <h2><strong>CONTACT</strong></h2>
    <p>Feel free to reach out via email or social media.</p>

    <div class="social-icons">
      <a href="mailto:mantas.kru.2@gmail.com" target="_blank">
        <img src="Photos/Gmail.png" alt="Gmail">
      </a>
      <a href="https://www.facebook.com/profile.php?id=100009086828868" target="_blank">
        <img src="Photos/Facebook.png" alt="Facebook">
      </a>
      <a href="https://www.youtube.com/@CubeDev-q9j" target="_blank">
        <img src="Photos/youtube.png" alt="YouTube">
      </a>
    </div>
  </section>

</body>
</html>
