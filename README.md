<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Filmes</title>
    <link rel="icon" href="img/icon.png">
</head>
<body>

<!--NavBar-->
    <nav class="navbar col-12 position-fixed bg-dark navbar-expand-lg" data-bs-theme="dark" style="z-index: 999;">
      <div class="container-fluid col-11">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#filmes">Filmes</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#conteudo">Conteúdo</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#footer">Direitos</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>

<!-- Carousel -->
      <div id="carouselExampleAutoplaying" class="carousel slide" data-bs-ride="carousel">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <img src="img/walle.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/sennhor.png" class="d-block w-100" alt="...">
          </div>
          <div class="carousel-item">
            <img src="img/missao.png" class="d-block w-100" alt="...">
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleAutoplaying" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>

      <br><br>
<!-- Cards -->
<!-- Card 1 -->
      <h2 id="filmes" class="text-center">Filmes</h2>
      <div class="row row-cols-1 row-cols-md-3 g-4 col-11 m-auto">
        <div class="col">
          <div class="card">
            <img src="img/cardwalle.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Wall-E</h5>
              <p class="card-text">"Wall-E" é um filme de 2008, dirigido por "Andrew Staton" e indicado ao Oscar de melhor animação.</p>
<!-- Button trigger modal -->
              <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModal">
                Clique para saber mais...
              </button>
<!-- Modal -->
              <div class="modal fade" id="exampleModal" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                <div class="modal-dialog">
                  <div class="modal-content">
                    <div class="modal-header">
                      <h1 class="modal-title fs-5" id="exampleModalLabel">Sinopse:</h1>
                      <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                    </div>
                    <div class="modal-body">
                      <img src="img/modalwalle.jpeg" class="card-img-top" alt="">
                      <br><br>
                      Após entulhar a Terra de lixo e poluir a atmosfera com gases tóxicos, a humanidade deixou o planeta e passou a viver em uma gigantesca nave. O plano era que o retiro durasse alguns poucos anos, com robôs sendo deixados para limpar o planeta. WALL-E é o último destes robôs, e sua vida consiste em compactar o lixo existente no planeta. Até que um dia surge repentinamente uma nave, que traz um novo e moderno robô: Eva. A princípio curioso, WALL-E se apaixona e resolve segui-la por toda a galáxia.
                    </div>
                    <div class="modal-footer">
                      <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Fechar</button>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

<!-- Card 2 -->
        <div class="col">
          <div class="card">
            <img src="img/cardaneis.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">O Senhor dos Anéis: A Sociedade do Anel</h5>
              <p class="card-text">Lançado em 2002, este filme é um sucesso até os dias de hoje.</p>
              <!-- Button trigger modal -->
                <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModall">
                  Clique para saber mais...
                </button>

                <!-- Modal -->
                <div class="modal fade" id="exampleModall" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                  <div class="modal-dialog">
                    <div class="modal-content">
                      <div class="modal-header">
                        <h1 class="modal-title fs-5" id="exampleModalLabel">Sinopse:</h1>
                        <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                      </div>
                      <div class="modal-body">
                        <img src="img/modalsenhor.png" class="card-img-top" alt="">
                        Em uma terra fantástica e única, um hobbit recebe de presente de seu tio um anel mágico e maligno que precisa ser destruído antes que caia nas mãos do mal. Para isso, o hobbit Frodo tem um caminho árduo pela frente, onde encontra perigo, medo e seres bizarros. Ao seu lado para o cumprimento desta jornada, ele aos poucos pode contar com outros hobbits, um elfo, um anão, dois humanos e um mago, totalizando nove seres que formam a Sociedade do Anel.
                      </div>
                      <div class="modal-footer">
                        <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                        <button type="button" class="btn btn-primary">Save changes</button>
                      </div>
                    </div>
                  </div>
                </div>
                            </div>
                          </div>
                        </div>
        

<!-- Card 3 -->
        <div class="col">
          <div class="card">
            <img src="img/cardimf.png" class="card-img-top" alt="...">
            <div class="card-body">
              <h5 class="card-title">Missão Impossível</h5>
              <p class="card-text">Lançado em 1996, este filme é o primeiro de uma saga que se mostra rentável até os dias atuais.</p>
              <!-- Button trigger modal -->
                  <button type="button" class="btn btn-primary" data-bs-toggle="modal" data-bs-target="#exampleModa">
                    Clique para saber mais...
                  </button>
                  <!-- Modal -->
                  <div class="modal fade" id="exampleModa" tabindex="-1" aria-labelledby="exampleModalLabel" aria-hidden="true">
                    <div class="modal-dialog">
                      <div class="modal-content">
                        <div class="modal-header">
                          <h1 id="modal1" class="modal-title fs-5" id="exampleModalLabel">Sinopse:</h1>
                          <button type="button" class="btn-close" data-bs-dismiss="modal" aria-label="Close"></button>
                        </div>
                        <div class="modal-body">
                          <img src="img/modalimpossivel.png" class="card-img-top" alt="">
                          <br><br>
                          O agente do governo Ethan Hunt e seu mentor, Jim Phelps, embarcam em uma missão secreta que toma um rumo desastroso: Jim é morto e Ethan torna-se o principal suspeito do assassinato. Em fuga, Hunt recruta o brilhante Luther Stickell e o piloto Franz Krieger para ajudá-lo a entrar no prédio da CIA, fortemente vigiado, a fim de pegar um arquivo de computador confidencial que pode provar a sua inocência.
                        </div>
                        <div class="modal-footer">
                          <button type="button" class="btn btn-secondary" data-bs-dismiss="modal">Close</button>
                          <button type="button" class="btn btn-primary">Save changes</button>
                        </div>
                      </div>
                    </div>
                  </div>
            </div>
          </div>
        </div>
      </div>

      <!-- Conteudo -->
      <br><br>
      <hr class="col-11 m-auto"/>
      <br>
      <div class="col-11 m-auto">
        <h2 id="conteudo" class="text-center">Meus filmes favoritos:</h2>
        <p class="text-center">Vejam um pouco dos meus filmes favoritos, esses são longas-metragem que me marcaram bastante.
        </p>
      </div>
      <hr class="col-11 m-auto">
      <br><br>

      <!-- Rodapé -->
      <footer id="footer" class="page-footer p-5 m-auto"
        style="background-color: #333;">
        <div class="text-center">
          <a href="#">@2023 Copyright: João Henrique de Oliveira Ribeiro</a>
        </div>
      </footer>

      <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-4bw+/aepP/YC94hEpVNVgiZdgIC5+VKNBQNGCHeKRQN+PtmoHDEXuppvnDJzQIu9" crossorigin="anonymous">
      <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.1/dist/js/bootstrap.bundle.min.js" integrity="sha384-HwwvtgBNo3bZJJLYd8oVXjrBZt8cqVSpeBNS5n7C8IVInixGAoxmnlMuBnhbgrkm" crossorigin="anonymous"></script>
</body>
</html>
