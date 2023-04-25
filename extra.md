<html>
  <head>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p" crossorigin="anonymous"></script>
    <style>
      .carousel-item img {
        max-height: 500px;
        margin: auto;
        display: block;
      }
      .carousel-control-prev, .carousel-control-next {
        filter: invert(1) sepia(1) saturate(5) hue-rotate(195deg);
      }
    </style>
  </head>
  <body>
    <div class="index-header">
      <h1>Extra Seed</h1>
      <p>Add an element of bootstrap to this page (ex. carousel) OR Add an element using Tailwind</p>
    </div>
    <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active">
          <img src="https://user-images.githubusercontent.com/109186517/234167705-e78f850c-535b-47ed-b6e3-33f8575bbbfd.png" alt="First slide">
        </div>
        <div class="carousel-item">
          <img src="https://user-images.githubusercontent.com/109186517/234167733-ddb5c0c4-7efb-4580-af45-cabf98b904f7.png" alt="Second slide">
        </div>
        <div class="carousel-item">
          <img src="https://user-images.githubusercontent.com/109186517/234167779-4156769c-5850-41f3-beab-fea4d557091f.png" alt="Third slide">
        </div>
      </div>
      <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Previous</span>
      </button>
      <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="visually-hidden">Next</span>
      </button>
    </div>