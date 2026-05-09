<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>YOUR ARTIST NAME</title>

  <style>
    *{
      margin:0;
      padding:0;
      box-sizing:border-box;
      font-family:Arial, Helvetica, sans-serif;
    }

    body{
      background:#0d0d0d;
      color:white;
      overflow-x:hidden;
    }

    header{
      height:100vh;
      display:flex;
      flex-direction:column;
      justify-content:center;
      align-items:center;
      text-align:center;
      background:linear-gradient(
        180deg,
        #1a1a1a,
        #0d0d0d
      );
    }

    h1{
      font-size:5rem;
      letter-spacing:8px;
      text-transform:uppercase;
    }

    .subtitle{
      margin-top:10px;
      color:#888;
      font-size:1.2rem;
    }

    nav{
      margin-top:30px;
      display:flex;
      gap:20px;
      flex-wrap:wrap;
      justify-content:center;
    }

    nav a{
      text-decoration:none;
      color:white;
      padding:12px 22px;
      border:1px solid #333;
      transition:0.3s;
      border-radius:10px;
    }

    nav a:hover{
      background:white;
      color:black;
    }

    section{
      padding:100px 10%;
    }

    h2{
      font-size:2.5rem;
      margin-bottom:20px;
    }

    .card{
      background:#141414;
      padding:25px;
      border-radius:20px;
      margin-top:20px;
      border:1px solid #222;
    }

    .music-grid{
      display:grid;
      grid-template-columns:repeat(auto-fit, minmax(250px, 1fr));
      gap:20px;
    }

    iframe{
      width:100%;
      height:200px;
      border:none;
      border-radius:15px;
    }

    footer{
      text-align:center;
      padding:40px;
      color:#666;
      border-top:1px solid #222;
    }

    .glow{
      text-shadow:
        0 0 10px #ffffff22,
        0 0 20px #ffffff22;
    }
  </style>
</head>

<body>

  <!-- HERO SECTION -->
  <header>
    <h1 class="glow">YOUR NAME</h1>

    <!-- EDIT THIS -->
    <p class="subtitle">
      experimental • glitch • ambient • underground
    </p>

    <!-- EDIT LINKS -->
    <nav>
      <a href="https://spotify.com" target="_blank">Spotify</a>

      <a href="https://soundcloud.com" target="_blank">SoundCloud</a>

      <a href="https://youtube.com" target="_blank">YouTube</a>

      <a href="https://instagram.com" target="_blank">Instagram</a>
    </nav>
  </header>

  <!-- ABOUT -->
  <section>
    <h2>About</h2>

    <div class="card">
      <!-- EDIT THIS -->
      <p>
        Write your artist description here.
        Talk about your sound, inspiration,
        albums, aesthetic, or anything else.
      </p>
    </div>
  </section>

  <!-- MUSIC -->
  <section>
    <h2>Music</h2>

    <div class="music-grid">

      <!-- SONG / ALBUM CARD -->
      <div class="card">
        <h3>Album / Song Name</h3>

        <!-- REPLACE WITH EMBED LINK -->
        <iframe
          src="https://open.spotify.com/embed/track/YOURTRACK"
          allowfullscreen=""
          loading="lazy">
        </iframe>
      </div>

      <div class="card">
        <h3>Another Release</h3>

        <iframe
          src="https://open.spotify.com/embed/track/YOURTRACK"
          allowfullscreen=""
          loading="lazy">
        </iframe>
      </div>

    </div>
  </section>

  <!-- CONTACT -->
  <section>
    <h2>Contact</h2>

    <div class="card">
      <!-- EDIT EMAIL -->
      <p>Email: youremail@gmail.com</p>
    </div>
  </section>

  <footer>
    © 2026 YOUR NAME
  </footer>

</body>
</html>
