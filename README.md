<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfolio</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
    }
    .container {
      max-width: 960px;
      margin: auto;
    }
    .novels {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .novel {
      margin: 10px;
    }
    .novel img {
      max-width: 200px;
      height: auto;
    }
    .images {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }
    .image {
      margin: 10px;
    }
    .image img {
      max-width: 300px;
      height: auto;
    }
  </style>
</head>
<body>

  <header>
    <h1>Welcome to My Portfolio</h1>
    <p>This is a collection of my novels and images.</p>
  </header>

  <section class="novels">
    <div class="container">
      <h2>Novels</h2>
      <div class="novel">
        <img src="novel1.jpg" alt="Novel 1">
        <p>Novel 1</p>
      </div>
      <div class="novel">
        <img src="novel2.jpg" alt="Novel 2">
        <p>Novel 2</p>
      </div>
      <div class="novel">
        <img src="novel3.jpg" alt="Novel 3">
        <p>Novel 3</p>
      </div>
    </div>
  </section>

  <section class="images">
    <div class="container">
      <h2>Images</h2>
      <div class="image">
        <img src="image1.jpg" alt="Image 1">
        <p>Image 1</p>
      </div>
      <div class="image">
        <img src="image2.jpg" alt="Image 2">
        <p>Image 2</p>
      </div>
      <div class="image">
        <img src="image3.jpg" alt="Image 3">
        <p>Image 3</p>
      </div>
    </div>
  </section>

</body>
</html>
