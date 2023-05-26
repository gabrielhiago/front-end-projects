<!--# front-end-projects
Projetos de sites desenvolvidos utilizando HTML | CSS | JS e outras tecnologias de desenvolvimento web

1. Projeto de Site sobre a história do Android <a href="https://gabriel-hiago95.github.io/front-end-projects/android-project/">Ver projeto</a>-->

<!--<!DOCTYPE html>-->
<html lang="pt-br">
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <title>Meus Projetos Front-End</title>
  <!--<link rel="stylesheet" type="text/css" href="style.css">-->
  <script src="https://cdn.lordicon.com/bhenfmcm.js" defer></script>

  <style>
    @charset 'utf-8';

    @import url('https://fonts.googleapis.com/css2?family=Ubuntu:ital,wght@0,300;0,400;0,500;0,700;1,300;1,400;1,500;1,700&display=swap');

    :root {
      --fonteTitulo: 'Ubuntu', sans-serif;
      --fonteSubtitulo: 'Ubuntu', sans-serif;
      --fonteCorpo: 'Ubuntu', sans-serif;
    }

    body {
        font-family: var(--fonteCorpo);
        font-weight: 300;
        margin: 0px;
        padding: 0px;
        background-color: rgb(196, 196, 196);
        color: black;
      }

      h1 {
        font-family: var(--fonteTitulo);
        font-weight: 700;
      }

      h2 {
        font-family: var(--fonteSubtitulo);
        font-weight: 700;
      }

      h3 {
        font-family: var(--fonteSubtitulo);
        font-weight: 500;
      }
      
      header {
        background-color: black;
        color: #fff;
        padding: 20px;
        text-align: center;
      }

      #sobre, #projetos {
        padding: 20px;
      }

      .container {
        max-width: 1200px;
        margin: 0 auto;
        padding: 0 20px;
      }

      .container > a {
        text-decoration: none;
      }
      
      nav ul {
        list-style-type: none;
        margin: 0;
        padding: 0;
      }
      
      nav ul li {
        display: inline;
        margin-right: 10px;
      }
      
      nav ul li a {
        color: #fff;
        text-decoration: none;
        transition: color 0.3s ease;
      }
      
      nav ul li a:hover {
        color: #ff9900;
      }
      
      section {
        padding: 50px 0;
      }

      .container > h2 {
        margin-bottom: 25px;
      }
      
      .projeto {
        display: flex;
        align-items: center;
        margin-bottom: 20px;
        transition: transform 0.3s ease;
        background-color: white;
        border-radius: 5px;
        box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
      }
      
      .projeto img {
        width: 200px;
        margin-right: 20px;
        border-radius: 5px 0 0 5px;
      }
      
      .projeto-info {
        display: flex;
        flex: 1;
        justify-content: space-between;
        align-items: center;
        padding-right: 20px;
        background-color: #ff9900;
        margin: 10px 10px 10px 0px;
      }
      
      .projeto p {
        margin-top: 10px;
        line-height: 1.5;
        color: black;
      }
      
      .projeto:hover {
        transform: translateY(-5px);
        box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      }

      .projeto-icone {
        width:100px;
        height:100px;
      }

      .container-projeto {
        margin-left: 5%;
      }
      
      footer {
        background-color: black;
        color: white;
        padding: 20px;
        text-align: center;
      }

      footer > p > a {
        text-decoration: none;
        font-family: var(--fonteCorpo);
        font-weight: 700;
        position: relative;
        font-size: 18px;
        color: white;
      }

      footer > p > a:hover {
        text-decoration: underline;
        font-family: var(--fonteCorpo);
        font-weight: 700;
        position: relative;
        font-size: 18px;
        color: white;
      }

      /* Estilo para os botões */
      .btn-projeto {
        position: relative;
        margin: auto;
        padding: 12px 18px;
        transition: all 0.2s ease;
        border: none;
        background: none;
      }
      
      .btn-projeto:before {
        content: "";
        position: absolute;
        top: 0;
        left: 0;
        display: block;
        border-radius: 50px;
        background: black;
        width: 45px;
        height: 45px;
        transition: all 0.3s ease;
      }

      a {
        text-decoration: none;
        font-family: var(--fonteCorpo);
        font-weight: 400;
        position: relative;
        font-size: 18px;
        color: white;
      }
      
      .btn-projeto svg {
        position: relative;
        top: 0;
        margin-left: 10px;
        fill: none;
        stroke-linecap: round;
        stroke-linejoin: round;
        stroke: white;
        stroke-width: 2;
        transform: translateX(-5px);
        transition: all 0.3s ease;
      }
      
      .btn-projeto:hover:before {
        width: 100%;
        background: black;
      }
      
      .btn-projeto:hover svg {
        transform: translateX(0);
      }
      
      .btn-projeto:active {
        transform: scale(0.95);
      }
  </style>
</head>
<body>
  <header>
    <div class="container">
      <h1>Meus Projetos</h1>
    </div>
  </header>

  <main>
    <section id="sobre">
      <div class="container">
        <h2>Sobre</h2>
        <p>
          Olá, me chamo Gabriel Hiago e sou estudante de programação web front-end. Esta é uma pequena amostra de alguns projetos que desenvolvi utilizando HTML | CSS | JS, espero que goste.
        </p>
      </div>
    </section>
    <section id="projetos">
      <div class="container">
        <h2>Projetos</h2>
        <div class="projeto">
          <lord-icon
              src="https://cdn.lordicon.com/qhgmphtg.json"
              trigger="hover"
              colors="primary:#242424,secondary:#e88c30" class="projeto-icone">
          </lord-icon>
          <div class="projeto-info">
            <div class="container-projeto">
              <h3>Projeto Android</h3>
              <p>Site simples sobre a história do mascote do Android.</p>
            </div>
            <div class="container-btn">
              <button class="btn-projeto">
    
                <a href="https://gabriel-hiago95.github.io/front-end-projects/android-project/" target="_blank">
                  <span>Ver Projeto</span>
                </a>
                <svg viewBox="0 0 13 10" height="10px" width="15px">
    
                  <path d="M1,5 L11,5"></path>
                  <polyline points="8 1 12 5 8 9"></polyline>
    
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div class="projeto">
          <lord-icon
              src="https://cdn.lordicon.com/qhgmphtg.json"
              trigger="hover"
              colors="primary:#242424,secondary:#e88c30" class="projeto-icone">
          </lord-icon>
          <div class="projeto-info">
            <div class="container-projeto">
              <h3>Projeto Cordel Moderno</h3>
              <p>Site simples com um poema de Milton Duarte sobre tecnologia.</p>
            </div>
            <div class="container-btn">
              <button class="btn-projeto">
    
                <a href="https://gabriel-hiago95.github.io/front-end-projects/cordel-project/" target="_blank">
                  <span>Ver Projeto</span>
                </a>
                <svg viewBox="0 0 13 10" height="10px" width="15px">
    
                  <path d="M1,5 L11,5"></path>
                  <polyline points="8 1 12 5 8 9"></polyline>
    
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p>&copy; Projeto Desenvolvido por
      <a href="https://github.com/Gabriel-Hiago95" target="_blank">Gabriel Hiago</a>
    </p>
  </footer>
</body>
</html>
