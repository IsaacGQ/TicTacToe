# TicTacToe
Game
/*#################################################################################

UNIVERSIDAD AUTOTONOMA DE BAJA CALIFORNIA Facultad de Ingeniería, Arquitectura y Diseño (FIAD)

MIEMBROS DE EQUIPO: -ISAAC GUTIERREZ QUINTERO -BIANCA NOELIA OROZCO MORAN -JOSE FRANCISCO JUAREZ ACEVEZ -ESTEFANIA TELLO MENDOZA

21/10 2023 Install Libraries From: Adafruit_GFX.h 
https://github.com/adafruit/Adafruit-GFX-Library Adafruit_TFTLCD.h 
https://github.com/adafruit/TFTLCD-Library TouchScreen.h 
https://github.com/adafruit/Adafruit_TouchScreen

###################################################################################*/# 

<!DOCTYPE html>
<html>

<head>
  <!-- Metadatos básicos -->
  <meta charset="utf-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <!-- Metadatos para dispositivos móviles -->
  <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no" />
  <!-- Metadatos del sitio web -->
  <meta name="keywords" content="" />
  <meta name="description" content="" />
  <meta name="author" content="" />

  <title>ESO TILIN</title>

  <!-- Estilos CSS de Bootstrap -->
  <link rel="stylesheet" type="text/css" href="css/bootstrap.css" />

  <!-- Fuente personalizada desde Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap" rel="stylesheet">

  <!-- Estilos personalizados para esta plantilla -->
  <link href="css/style.css" rel="stylesheet" />
  <!-- Estilos responsivos -->
  <link href="css/responsive.css" rel="stylesheet" />
</head>

<body>
  <div class="hero_area">
    <!-- Sección de encabezado -->
    <header class="header_section">
      <div class="container-fluid">
        <nav class="navbar navbar-expand-lg custom_nav-container">
          <a class="navbar-brand" href="index.html">
            <img src="images/logo.png" alt="" />
            <span>
              Tic Tac Toe
            </span>
          </a>
          <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
            <span class="navbar-toggler-icon"></span>
    </header>
    <!-- Fin de la sección de encabezado -->
    <!-- Sección de slider -->
    <section class="slider_section ">
      <div class="carousel_btn-container">
        <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
          <span class="sr-only">Previous</span>
        </a>
        <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
          <span class="sr-only">Next</span>
        </a>
      </div>
      <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active">01</li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1">02</li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2">03</li>
        </ol>
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="container-fluid">
              <div class="row">
                <div class="col-md-5 offset-md-1">
                  <div class="detail-box">
                    <h1>
                      Tic 
                      Tac 
                      Toe Cimarron
                    </h1>
                    <p>
                        Microcontrolador de Arduino programado en C++ para desarrollo de juego tic tac toe
                        existen 2 modos de juego, el solitario (contra robot), y el de ambos jugadores.
                        <br />
                        <br />
                        el juego "Tic Tac Toe" (también conocido como "Tres en Línea" o "Gato" en algunos 
                        lugares) es un juego de estrategia para dos jugadores que se juega en un tablero de 
                        3x3. El objetivo del juego es lograr que tres de tus fichas (ya sea X o O) se alineen
                        en línea, ya sea horizontal, vertical o diagonal, antes que tu oponente.
                    </p>
                    <div class="btn-box">
                        <a href="https://github.com/IsaacGQ/TicTacToe" class="btn-1" target="_blank">
                            Ver más
                        </a>
                        <a href="" class="btn-2">
                            Ver video
                        </a>
                    </div>
                  </div>
                </div>
                <div class="offset-md-1 col-md-4 img-container">
                  <div class "img-box">
                    <img src="images/slider-img.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item ">
            <div class="container-fluid">
              <div class="row">
                <div class="col-md-5 offset-md-1">
                  <div class="detail-box">
                    <h1>
                       <br>
                     TIC TAC TOE<br>
                      (Modo Solitario)
                    </h1>
                    <p>
                        El modo de juego solitario te permite retar a la computadora, que utiliza una 
                        inteligencia programada con 10 mil patrones de movimientos para calcular la opción
                        más eficiente y ganar. Esta característica añade un desafío estratégico emocionante
                        al juego donde pondras en prueba tus habilidades mentales.
                    </p>
                    <div class="btn-box">
                        <a href="https://github.com/IsaacGQ/TicTacToe" class="btn-1">
                            Ver más
                        </a>
                      <a href="" class="btn-2">
                         Ver video
                      </a>
                    </div>
                  </div>
                </div>
                <div class="offset-md-1 col-md-4 img-container">
                  <div class="img-box">
                    <img src="images/slider-img.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="carousel-item ">
            <div class="container-fluid">
              <div class "row">
                <div class="col-md-5 offset-md-1">
                  <div class="detail-box">
                      <h1>
                          TIC TAC TOE <br>
                          (Modo Duo) <br>
                      </h1>
                      <p>
                          Este modo de juego existe para que el jugador pueda
                          retar a cualquier persona y/o amigo, donde uno usara
                          Os y otro usará Xs, donde tendrán que competir y encontrar
                          la forma de obtener la victoria.
                      </p>
                    <div class="btn-box">
                        <a href="https://github.com/IsaacGQ/TicTacToe" class="btn-1">
                            Ver más
                        </a>
                        <a href="" class="btn-2">
                            Ver video
                        </a>
                    </div>
                  </div>
                </div>
                <div class="offset-md-1 col-md-4 img-container">
                  <div class="img-box">
                    <img src="images/slider-img.png" alt="">
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>

    </section>
    <!-- Fin de la sección del slider -->
  </div>

  <!-- Sección de experiencia -->
  <section class="experience_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-md-5">
          <div class="img-box">
            <img src="images/experience-img.jpg" alt="">
          </div>
        </div>
        <div class="col-md-7">
          <div class="detail-box">
            <div class="heading_container">
              <h2>
                Resumen
              </h2>
            </div>
            <p>
                Este proyecto tiene como objetivo proporcionar
                una experiencia educativa en la introducción a los
                microcontroladores de manera accesible y didáctica.
                Utiliza el versátil microcontrolador reprogramable
                Arduino y el lenguaje de programación C++ para crear
                un juego clásico de Tic Tac Toe. Además, presenta
                información clave sobre el proyecto a través de una
                página web, aprovechando las habilidades adquiridas
                en el curso de Desarrollo de Aplicaciones Web, que
                incluye la creación de páginas en HTML y estilización
                con hojas de estilo (CSS).
                <br />
                <br />
                Este enfoque interdisciplinario combina la programación
                de microcontroladores y el desarrollo web para proporcionar
                a los participantes una experiencia de aprendizaje integral.
                El proyecto pretende no solo enseñar las habilidades técnicas
                necesarias, sino también mostrar cómo estas disciplinas pueden
                complementarse y enriquecerse mutuamente. ¡Bienvenidos a la
                emocionante aventura del Tic Tac Toe con Arduino y el
                desarrollo web!
            </p>
          </div>
        </div> 
      </div>
    </div>
  </section>
  <!-- Fin de la sección de experiencia -->

  <!-- Sección de categorías -->
  <section class="category_section layout_padding">
    <div class="container">
      <div class="heading_container">
        <h2>
          Materiales utilizados 
        </h2>
      </div>
      <div class="category_container">
        <div class="box">
          <div class="img-box">
            <img src="images/c1.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              Botones de 4 pines
            </h5>
          </div>
        </div>
        <div class="box">
          <div class="img-box">
            <img src="images/c2.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              Resistencias de 220 Ohms
            </h5>
          </div>
        </div>
        <div class="box">
          <div class="img-box">
            <img src="images/c3.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              Arduino UNO
            </h5>
          </div>
        </div>
        <div class="box">
          <div class="img-box">
            <img src="images/c4.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              Jumpers
            </h5>
          </div>
        </div>
        <div class="box">
          <div class="img-box">
            <img src="images/c5.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              9 LED´s
            </h5>
          </div>
        </div>
        <div class="box">
          <div class="img-box">
            <img src="images/c6.png" alt="">
          </div>
          <div class="detail-box">
            <h5>
              Display táctil 
            </h5>
          </div>
        </div>
      </div>
    </div>
  </section>
  <!-- Fin de la sección de categorías -->

  <!-- Sección "Acerca de" -->
  <section class="about_section layout_padding">
    <div class="container">
      <div class="row">
        <div class="col-md-10 col-lg-9 mx-auto">
          <div class="img-box">
            <img src="images/about-img.jpg" alt="">
          </div>
        </div>
      </div>
      <div class="detail-box">
        <h2>
          Código fuente
        </h2>
        <p>
            En la ejecución de este proyecto, creamos dos variantes del juego.
            En una de ellas, incorporamos una interfaz táctil, mientras que en
            la otra diseñamos un circuito utilizando LEDs y cables de conexión.
            Para cada versión, desarrollamos un código específico en función de
            las funcionalidades deseadas. Puede acceder a los respectivos 
            códigos en nuestro repositorio de GitHub, el cual está disponible
            para su descarga desde este enlace.
        </p>
        <a href="https://github.com/IsaacGQ/TicTacToe" target="_blank">
          Código aquí
        </a>
      </div>
    </div>
  </section>
  <!-- Fin de la sección "Acerca de" -->

  <!-- Sección de pasos a seguir -->
  <section class="freelance_section ">
      <div id="accordion">
          <div class="container-fluid">
              <div class="row">
                  <div class="col-md-5 offset-md-1">
                      <div class="detail-box">
                          <div class="heading_container">
                              <h2>
                                  Pasos a seguir
                              </h2>
                          </div>
                          <div class="tab_container">
                              <div class="t-link-box" aria-expanded="true">
                                  <div class="img-box">
                                      <img src="images/f1.png" alt="">
                                  </div>
                                  <div class="detail-box">
                                      <h3>
                                          Conexión de los LEDs
                                      </h3>
                                      <h5>
                                          Conecta los ánodos de los LEDs (los terminales más largos) 
                                          a las salidas digitales de Arduino. Cada LED se conectará a
                                          una de las casillas del tablero del juego. 
                                      </h5>
                                  </div>
                              </div>
                              <div class="t-link-box" aria-expanded="false">
                                  <div class="img-box">
                                      <img src="images/f2.png" alt="">
                                  </div>
                                  <div class="detail-box">
                                      <h3>
                                          Conexión de botones
                                      </h3>
                                      <h5>
                                          Conecta los botones a las entradas digitales de Arduino. 
                                          Los botones permitirán a los jugadores seleccionar las casillas
                                          del tablero.
                                      </h5>
                                  </div>
                              </div>
                              <div class="t-link-box" aria-expanded="false">
                                  <div class="img-box">
                                      <img src="images/f3.png" alt="">
                                  </div>
                                  <div class="detail-box">
                                      <h3>
                                          Programación
                                      </h3>
                                      <h5>
                                          Programa Arduino utilizando C++ para controlar el juego. 
                                          Define las reglas del juego y cómo se actualizará el tablero
                                          en función de las selecciones de los jugadores.
                                      </h5>
                                  </div>
                              </div>
                              <div class="t-link-box" aria-expanded="false">
                                  <div class="img-box">
                                      <img src="images/f4.png" alt="">
                                  </div>
                                  <div class="detail-box">
                                      <h3>
                                          Jugar
                                      </h3>
                                      <h5>
                                          ¡Es hora de jugar! Uno de los jugadores selecciona una casilla
                                          en el tablero utilizando un botón, y el otro jugador (o la computadora)
                                          selecciona otra casilla. El juego continúa hasta que alguien gane o
                                          se produzca un empate.
                                      </h5>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <div class="offset-md-1 col-md-4 img-container">
                      <div class="img-box">
                          <img src="images/freelance-img.jpg" alt="">
                      </div>
                  </div>
              </div>
          </div>
      </div>
  </section>
  <!-- Fin de la sección de pasos a seguir -->

  <!-- Sección de contacto -->
  <section class="contact_section layout_padding">
    <div class="container">
      <div class="heading_container">
        <h2>
          Contacto
        </h2>
      </div>
      <div class="contact-form">
        <form action="mailto:example@example.com" method="post">
          <div>
            <input type="text" placeholder="Nombre" name="Name" id="name" required>
          </div>
          <div>
            <input type="email" placeholder="Correo electrónico" name="Email" id="email" required>
          </div>
          <div>
            <input type="text" placeholder="Mensaje" name="Message" id="message" required>
          </div>
          <div class="btn-box">
            <button type="submit" class="btn-1">
              Enviar mensaje
            </button>
          </div>
        </form>
      </div>
    </div>
  </section>
  <!-- Fin de la sección de contacto -->

  <!-- Pie de página -->
  <footer class="footer_section">
    <div class="container">
      <div class="row">
        <div class="col-md-8">
          <div class="footer_contact">
            <div class="footer_logo">
              <a href="index.html">
                <img src="images/logo.png" alt="">
                <span>
                  Tic Tac Toe
                </span>
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="footer_link-box">
            <div class="footer_links">
              <ul>
                <li>
                  <a href="index.html">
                    Inicio
                  </a>
                </li>
                <li>
                  <a href="#about">
                    Acerca de
                  </a>
                </li>
                <li>
                  <a href="#contact">
                    Contacto
                  </a>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- Fin del pie de página -->

  <!-- Scripts de JavaScript -->
  <script src="js/jquery-3.4.1.min.js"></script>
  <script src="js/popper.min.js"></script>
  <script src="js/bootstrap.js"></script>
  <script src="js/custom.js"></script>
</body>

</html>
