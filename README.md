<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=, initial-scale=1.0">
    <title>Loja de Roupas Lafemme</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4Q6Gf2aSP4eDXB8Miphtr37CMZZQ5oXLH2yaXMJ2w8e2ZtHTl7GptT4jmndRuHDT" crossorigin="anonymous">
  </head>
</head>
<body>
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.6/dist/js/bootstrap.bundle.min.js" integrity="sha384-j1CDi7MgGQ12Z7Qab0qlWQ/Qqz24Gc6BM0thvEMVjHnfYGF0rmFCozFSxQBxwHKO" crossorigin="anonymous"></script>
  </body>
<!--NAVEBAR-->
<nav class="navbar navbar-expand-lg bg-body-tertiary position-relative">
  <div class="container-fluid">

    <!-- Lado esquerdo -->
    <a class="navbar-brand" href="#">Bem Vindo</a>

    <!-- Botão do menu em mobile -->
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse"
      data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false"
      aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>

    <!-- Texto CENTRAL - posição absoluta -->
    <div class="position-absolute top-50 start-50 translate-middle">
      <h3 class="fw-bold m-0">LA FEMME</h3>
    </div>

    <!-- Itens colapsáveis -->
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <!-- Lado esquerdo -->
      <ul class="navbar-nav me-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
      </ul>

      <!-- Lado direito -->
      <ul class="navbar-nav mb-2 mb-lg-0">
        <li class="nav-item">
          <a class="nav-link" href="#">Contato</a>
        </li>
      </ul>

      <!-- Barra de busca -->
      <form class="d-flex ms-3" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search" />
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>

<!--Carrousel-->
<div>
  <div id="carouselExample" class= "carousel slide">
  <div class="carousel-inner" style="margin: 10px auto ; width: 100%;">
    <div class="carousel-item active">
      <img src="IMG/1.png" class="d-block mx-auto" style="width: 40%" alt="1">
    </div>
    <div class="carousel-item">
      <img src="IMG/2.png" class="d-block mx-auto" style="width: 40%" alt="1">
    </div>
    <div class="carousel-item">
      <img src="IMG/3.png" class="d-block mx-auto" style="width: 40%" alt="10">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
</div>

<!--Cards-->
<div class="container">
  <div class="row justify-content-between text-center">

    <!-- Card Esquerdo -->
    <div class="col-md-4">
      <div class="card mx-auto" style="width: 10rem;">
        <img src="IMG/3.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card Esquerdo</h5>
          <p class="card-text">Texto do card esquerdo.</p>
          <a href="#" class="btn btn-primary">Ação</a>
        </div>
      </div>
    </div>

    <!-- Card Central -->
    <div class="col-md-4">
      <div class="card mx-auto" style="width: 10rem;">
        <img src="IMG/2.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card Centro</h5>
          <p class="card-text">Texto do card central.</p>
          <a href="#" class="btn btn-primary">Ação</a>
        </div>
      </div>
    </div>

    <!-- Card Direito -->
    <div class="col-md-4">
      <div class="card mx-auto" style="width: 10rem;">
        <img src="IMG/1.png" class="card-img-top" alt="...">
        <div class="card-body">
          <h5 class="card-title">Card Direito</h5>
          <p class="card-text">Texto do card direito.</p>
          <a href="#" class="btn btn-primary">Ação</a>
        </div>
      </div>
    </div>

  </div>
</div>


<!--Footer-->
<footer class="bg-dark text-white text-center text-lg-start">
  <div class="text-center p-3">
    © 2023 Loja de Roupas Lafemme
    <a class="text-white" href="https://www.lafemme.com.br/">lafemme.com.br</a>
  </div>
</body>
</html>
