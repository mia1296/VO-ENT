<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>VO ENT | Music & Merch</title>
  <style>
    * { box-sizing: border-box; }
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #0f0f0f;
      color: #fff;
      text-align: center;
      padding: 50px 20px;
    }
    h1 {
      font-size: 3em;
      margin-bottom: 0.2em;
      letter-spacing: 1px;
    }
    p {
      font-size: 1.2em;
      margin-bottom: 2em;
    }
    .buttons {
      margin-bottom: 2em;
    }
    a.button {
      display: inline-block;
      padding: 15px 30px;
      margin: 10px;
      background: #f04e23;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      transition: background 0.3s ease;
    }
    a.button:hover {
      background: #c13b15;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 10px;
      margin-top: 20px;
      box-shadow: 0 0 15px rgba(0,0,0,0.5);
    }
    .video-container {
      position: relative;
      padding-bottom: 56.25%;
      height: 0;
      overflow: hidden;
      max-width: 100%;
      margin: 40px auto;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0,0,0,0.4);
    }
    .video-container iframe {
      position: absolute;
      top: 0; left: 0;
      width: 100%; height: 100%;
      border: 0;
    }
    .social {
      margin-top: 30px;
    }
    .social a {
      margin: 0 10px;
      color: #f04e23;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      margin-top: 50px;
      font-size: 0.9em;
      color: #aaa;
    }
  </style>
</head>
<body>
  <h1>🎧 VO ENT</h1>
  <p>Welcome to the VO Life!</p>

  <div class="buttons">
    <a class="button" href="https://music.apple.com/" target="_blank">🎵 Listen on Apple Music</a>
    <a class="button" href="https://youtube.com/" target="_blank">📺 Watch on YouTube</a>
  </div>

  <!-- You can upload your image as "cover.jpg" and replace this -->
  <img src="cover.jpg" alt="VO ENT Album Cover">

  <!-- YouTube Embed -->
  <div class="video-container">
    <iframe 
      src="https://www.youtube.com/embed/YOUR_VIDEO_ID" 
      title="VO ENT Video" 
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
      allowfullscreen>
    </iframe>
  </div>

  <div class="social">
    <p>Follow us:</p>
    <a href="https://youtube.com/" target="_blank">YouTube</a>
  </div>

  <footer>
    &copy; 2025 VO ENT. All rights reserved.
  </footer>
</body>
</html>
