
<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Madi — Personal Space</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      background: #f7f7f5;
      color: #222;
      font-family: Arial, sans-serif;
      line-height: 1.6;
    }

    header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 25px 8%;
      border-bottom: 1px solid #ddd;
    }

    .logo {
      font-size: 25px;
      font-weight: bold;
      letter-spacing: -1px;
    }

    nav a {
      color: #555;
      text-decoration: none;
      margin-left: 20px;
      font-size: 13px;
    }

    nav a:hover {
      color: black;
    }

    main {
      max-width: 1000px;
      margin: auto;
      padding: 70px 25px;
    }

    .intro {
      margin-bottom: 65px;
    }

    .intro h1 {
      font-size: clamp(45px, 9vw, 85px);
      letter-spacing: -5px;
      line-height: 1.1;
      margin: 15px 0;
    }

    .intro p {
      color: #777;
      max-width: 420px;
    }

    .small {
      font-size: 11px;
      letter-spacing: 3px;
      text-transform: uppercase;
      color: #888;
    }

    .photo {
      width: 100%;
      height: 400px;
      object-fit: cover;
      margin-bottom: 70px;
      background: #e5e5e5;
    }

    section {
      margin-bottom: 75px;
    }

    h2 {
      font-size: 25px;
      margin-bottom: 20px;
    }

    .about {
      max-width: 600px;
      color: #666;
    }

    .gallery {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 15px;
    }

    .gallery img {
      width: 100%;
      height: 270px;
      object-fit: cover;
      background: #e5e5e5;
    }

    .thought {
      border-top: 1px solid #ddd;
      padding: 20px 0;
      font-size: 19px;
    }

    footer {
      border-top: 1px solid #ddd;
      padding: 30px 8%;
      color: #888;
      font-size: 12px;
      display: flex;
      justify-content: space-between;
    }

    @media (max-width: 600px) {
      header {
        padding: 20px;
      }

      nav a {
        margin-left: 10px;
        font-size: 11px;
      }

      main {
        padding: 55px 20px;
      }

      .intro h1 {
        letter-spacing: -3px;
      }

      .photo {
        height: 250px;
      }

      .gallery img {
        height: 180px;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">MADI.</div>

    <nav>
      <a href="#about">About</a>
      <a href="#gallery">Gallery</a>
      <a href="#thoughts">Thoughts</a>
    </nav>
  </header>

  <main>

    <div class="intro">
      <div class="small">PERSONAL WEBSITE / 2026</div>

      <h1>Hello,<br>I'm Madi.</h1>

      <p>
        A little space on the internet.
        My photographs, thoughts, memories
        and everything in between.
      </p>
    </div>

    <!-- Главная фотография -->
    <img class="photo"
      src="https://images.unsplash.com/photo-1470770841072-f978cf4d019e?w=1200"
      alt="Main photograph">

    <section id="about">
      <div class="small">01 / ABOUT</div>
      <h2>A little about me.</h2>

      <p class="about">
        I'm Madi. I like observing the world,
        discovering new things, taking photographs
        and collecting moments.

        This website is my personal space.
        A place where I can leave a piece of myself.
      </p>
    </section>

    <section id="gallery">
      <div class="small">02 / GALLERY</div>
      <h2>Selected moments.</h2>

      <div class="gallery">
        <img src="https://images.unsplash.com/photo-1470252649378-9c29740c9fa8?w=800" alt="Nature">
        <img src="https://images.unsplash.com/photo-1519608487953-e999c86e7455?w=800" alt="Night">
        <img src="https://images.unsplash.com/photo-1472214103451-9374bd1c798e?w=800" alt="Landscape">
        <img src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?w=800" alt="Travel">
      </div>
    </section>

    <section id="thoughts">
      <div class="small">03 / THOUGHTS</div>
      <h2>Things I think about.</h2>

      <div class="thought">
        "Every day is a new page."
      </div>

      <div class="thought">
        "Sometimes the little things mean the most."
      </div>

      <div class="thought">
        "Life is made of moments."
      </div>
    </section>

  </main>

  <footer>
    <span>© 2026 MADI</span>
    <span>Made with curiosity.</span>
  </footer>

</body>
</html>
