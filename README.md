<!--Galler colection-->
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Image Gallery</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>

  <h1>🌟 My Awesome Gallery</h1>

  <!-- Filter Buttons -->
  <div class="filter-btns">
    <button data-filter="all">All</button>
    <button data-filter="nature">Nature</button>
    <button data-filter="city">City</button>
    <button data-filter="animals">Animals</button>
  </div>

  <!-- Image Gallery Grid -->
  <div class="gallery">
    <img src="https://source.unsplash.com/400x300/?nature,1" class="image nature" alt="Nature" />
    <img src="https://source.unsplash.com/400x300/?city,1" class="image city" alt="City" />
    <img src="https://source.unsplash.com/400x300/?animals,1" class="image animals" alt="Animals" />
    <img src="https://source.unsplash.com/400x300/?nature,2" class="image nature" alt="Nature" />
    <img src="https://source.unsplash.com/400x300/?city,2" class="image city" alt="City" />
    <img src="https://source.unsplash.com/400x300/?animals,2" class="image animals" alt="Animals" />
  </div>

  <!-- Lightbox View -->
  <div class="lightbox" id="lightbox">
    <span class="close">&times;</span>
    <img class="lightbox-content" id="lightbox-img">
    <div class="nav">
      <span id="prev">&#10094;</span>
      <span id="next">&#10095;</span>
    </div>
  </div>

  <script src="script.js"></script>
</body>
</html>
