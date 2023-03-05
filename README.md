
HTML
HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto 1</title>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="css/estilos.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@100;400;500&display=swap" rel="stylesheet">
</head>
<body>
    <header class="header" id="inicio">
        <img src="img/hamburguesa.svg" alt="" class="hamburguer">
        <nav class="menu-navegacion">
            <a href="#inicio">Inicio</a>
            <a href="#servicio">Servicio</a>
            <a href="#portafolio">Portafolio</a>
            <a href="#expertos">Expertos</a>
            <a href="#contacto">Contacto</a>
        </nav>
        <div class="contenedor head">
            <h1 class="titulo">Adentrate en el Mundo d ela Informatica</h1>
            <p class="copy">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Delectus sint corporis, laudantium dolores at quidem tempore voluptas excepturi vero! Ab, earum? Nobis, earum odit iure sit incidunt culpa quasi asperiores!</p>
        </div>
    </header>
    <main>
        <section class="services contenedor" id="servicio">
            <h2 class="subtitulo">Nuestro servicio</h2>
            <div class="contenedor-servicio">
                <img src="img/designer.png" alt="designador">
                <div class="designer">
                    <div class="service">
                        <h3 class="n-service"><span class="number">1</span>Diseño web</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                            Qui incidunt autem, deleniti accusantium magnam aliquam? 
                            Voluptatem aspernatur laborum rem sunt ex. Ut corporis consequuntur 
                            quis, dolores adipisci ducimus aliquam quos.</p>
                    </div>
                    <div class="service">
                        <h3 class="n-service"><span class="number">2</span>Diseño web</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                            Qui incidunt autem, deleniti accusantium magnam aliquam? 
                            Voluptatem aspernatur laborum rem sunt ex. Ut corporis consequuntur 
                            quis, dolores adipisci ducimus aliquam quos.</p>
                    </div>
                    <div class="service">
                        <h3 class="n-service"><span class="number">3</span>Diseño web</h3>
                        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. 
                            Qui incidunt autem, deleniti accusantium magnam aliquam? 
                            Voluptatem aspernatur laborum rem sunt ex. Ut corporis consequuntur 
                            quis, dolores adipisci ducimus aliquam quos.</p>
                    </div>
                    </div>
                </div>
        </section>
        <section class="gallery" id="portafolio">
            <div class="cotenedor">
                <h2 class="subtitulo">Galeria</h2>
                <div class="contenedor-galeria">
                    <img src="img/banner.jpg" alt=""class="galeria">
                    <img src="img/coffe.jpg" alt=""class="galeria">
                    <img src="img/marketing.jpg" alt=""class="galeria">
                    
                </div>
            </div>
        </section>
        <section class="imagen-light">
            <img src="img/menu.svg" alt="" class="close">
            <img src="img/windark.jpg" alt="" class="agregar-imagen">
        </section>
        <section class="contenedor" id="expertos">
            <h2 class="subtitulo">Expetos en:</h2>
            <section class="expert">
                <div class="cont-expert">
                    <img src="img/report.png" alt="expertos">
                    <h3 class="n-expert">Report</h3>
                </div>
                <div class="cont-expert">
                    <img src="img/videocall.png" alt="expertos">
                    <h3 class="n-expert">Video</h3>
                </div>
                <div class="cont-expert">
                    <img src="img/finance.png" alt="expertos">
                    <h3 class="n-expert">Finance</h3>
                </div>
            </section>
        </section>
    </main>
    <footer id="contacto">
        <div class="contenedor footer-content">
            <div class="contact-us">
                <h2 class="brand">GiacoX</h2>
                <p>Somos especialistas en informatica</p> 
            </div>
            <div class="social-media">
                <a href="./" class="social-media-icon">
                    <i class='bx bxl-facebook-circle'></i>
                </a>
                <a href="./" class="social-media-icon">
                    <i class='bx bxl-instagram-alt' ></i>
                </a>
                <a href="./" class="social-media-icon">
                    <i class='bx bxl-twitter' ></i>
                </a>
        </div>
        <div class="line">
        </div>
    </footer>
    <script src="js/menu.js"></script>
    <script src="js/lightbox.js"></script>
</body>
</html>
