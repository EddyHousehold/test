# test
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Photo Gallery</title>
  <style>
    body {
      font-family: sans-serif;
      text-align: center;
      background: #f4f4f4;
      margin: 0;
      padding: 1rem;
    }
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
      max-width: 1000px;
      margin: auto;
    }
    .gallery img {
      width: 100%;
      border-radius: 10px;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
  </style>
</head>
<body>
  <h1>My Photo Gallery</h1>
  <div class="gallery">
    <img src="images/photo1.jpg" alt="Photo 1">
    <img src="images/photo2.jpg" alt="Photo 2">
    <img src="images/photo3.jpg" alt="Photo 3">
    <!-- Add more images here -->
  </div>
</body>
</html>
