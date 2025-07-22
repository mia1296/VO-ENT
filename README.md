VO ENT
├── <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>VO – Official Site</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>VO</h1>
    <nav>
      <a href="#">Home</a>
      <a href="#">Music</a>
      <a href="#">Merch</a>
      <a href="#">Tour</a>
      <a href="#">VIP</a>
      <a href="#">Contact</a>
    </nav>
  </header>

  <section class="hero">
    <h2>🎤 Real Music. Real Stories.</h2>
    <p>🔥 New single “REAL ONES” out now.</p>
    <a href="https://music.apple.com/" class="btn">🔊 Listen Now</a>
    <a href="#" class="btn">👕 Shop Merch</a>
  </section>

  <section class="music">
    <h2>🎧 Listen to VO</h2>
    <p>Stream now on Apple Music & YouTube</p>
    <iframe width="300" height="170" src="https://https://youtu.be/-wpnJaxwnfg?si=gP2uFeUlwngqs9Cx/embed/your-video-id" frameborder="0" allowfullscreen></iframe>
    <!-- Replace with your video -->
  </section>

  <section class="merch">
    <h2>🛍 New Merch Drops</h2>
    <ul>
      <li>👕 REAL ONES T-shirt – $30</li>
      <li>🧢 Snapback – $25</li>
      <li>👟 Hoodie – Preorder $50</li>
    </ul>
    <a href="#" class="btn">View All Merch</a>
  </section>

  <section class="signup">
    <h2>📬 Join the VO Squad</h2>
    <p>Be the first to hear about drops, shows, and VIP perks.</p>
    <!-- Mailchimp embed goes here -->
  </section>

  <footer>
    <p>© 2025 VO. All rights reserved.</p>
    <p>
      <a href="#">https://youtube.com/playlist?list=RDEM-9iAf3ma2Wp8VUDcb8fSig&playnext=1&si=6-DFtJICbpqm0QuR</a> •
      <a href="#">TikTok</a> •
      <a href="#">Instagram</a>
    </p>
  </footer>
</body>
</html>         ← homepage
├── body {
  font-family: Arial, sans-serif;
  background: #111;
  color: #eee;
  margin: 0;
  padding: 0;
}

header {
  background: #000;
  padding: 20px;
  text-align: center;
}

header h1 {
  margin: 0;
  font-size: 2rem;
  color: #fff;
}

nav a {
  color: #aaa;
  margin: 0 10px;
  text-decoration: none;
}

.hero {
  text-align: center;
  padding: 40px 20px;
  background: #222;
}

.hero .btn {
  background: #e91e63;
  color: #fff;
  padding: 10px 20px;
  margin: 10px;
  text-decoration: none;
  display: inline-block;
}

section {
  padding: 30px;
  border-bottom: 1px solid #333;
}

footer {
  text-align: center;
  padding: 20px;
  font-size: 0.8rem;
  background: #000;
  color: #888;
}    ← styling
├── assets/
│   └── images/        ← (put your photos, logos, merch mockups here)
