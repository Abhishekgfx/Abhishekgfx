<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #ffffff;
      color: #000;
    }
    header {
      background-color: #001f3f;
      color: white;
      padding: 20px;
      text-align: center;
    }
    h1 {
      margin: 0;
    }
    .section-title {
      color: #001f3f;
      text-align: center;
      margin-top: 40px;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 20px;
    }
    .gallery img {
      width: 100%;
      border: 4px solid #001f3f;
      border-radius: 10px;
      transition: transform 0.3s;
    }
    .gallery img:hover {
      transform: scale(1.05);
    }
    footer {
      background-color: #001f3f;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 50px;
    }
  </style>
</head>
<body>
  <header>
    <h1>My Portfolio</h1>
    <p>Thumbnail Design Showcase</p>
  </header>

  <h2 class="section-title">Thumbnail Work</h2>
  <div class="gallery">
    <img src="/mnt/data/file-TFfaoMKS5SfcwkcDWhdSJX" alt="Thumbnail 1">
    <img src="/mnt/data/file-WrGT6Kt9uhkkGu25i35NUX" alt="Thumbnail 2">
    <img src="/mnt/data/file-8LnTVBXqR4WnA3agoP11z7" alt="Thumbnail 3">
    <img src="/mnt/data/file-FhpRmirBkP3PtuLao6k7Y3" alt="Thumbnail 4">
  </div>

  <footer>
    <p>Contact me at: yourname@example.com</p>
  </footer>
</body>
</html>


