<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>organos</title>
</head>

<body style="   margin: 0;">

    <link rel="stylesheet" type="text/css" href="css/styles1.css">

    <nav class="navbar">
        <ul class="nav-list">
                    <div class="navbar-logo">
    <img src="https://cdn-icons-png.flaticon.com/512/5783/5783338.png" alt="Logo"> 
            <li class="nav-item"><a href="pagprim.html">Inicio</a></li>
            <li class="nav-item"><a href="pag.html">Acerca de</a></li>
            <li class="nav-item dropdown">
                <a href="#" class="dropbtn">Más</a>
                <div class="dropdown-content">
                    <a href="pag.html">acerca de</a>
                    <a href="casos.html">casos</a>
                    <a href="#"> organos</a>
                </div>
            </li>
            <li class="nav-item search-item">
                <input type="text" class="search-input" placeholder="Buscar...">
                <button class="search-button">Buscar</button>
            </li>
        </ul>

    </nav>
</head>

    <div style="background-color: #ba4848; color: white; font-family: cursive;">
<marquee><h1 >  --------->Donacion de organos<---------  </h1></marquee>
</div>
 
    <style type="text/css">
        
         .navbar-logo {
      display: flex;
      align-items: center;
    }

    .navbar-logo img {
      height: 30px; /* Ajusta el tamaño del logo según necesites */
      margin-right: 10px;
    }

            section{
    display: flex;
    width: 1340px;
    height: 500px;

}
section img{
width: 0px;
flex-grow: 10;
object-fit: cover;
opacity: .8;
transition: .5s ease;
}

section img:hover{
    cursor: crosshair;
    width: 300px;
    opacity: 1;
    filter: contrast(120%);
    
}



    @keyframes diamond-in-hesitate {
  0% {
    clip-path: polygon(50% 50%, 50% 50%, 50% 50%, 50% 50%);
  }
  50% {
    clip-path: polygon(45% 50%, 50% 25%, 55% 50%, 50% 75%);
  }
  100% {
    clip-path: polygon(-50% 50%, 50% -50%, 150% 50%, 50% 150%);
  }
}

[transition-style="in:diamond:hesitate"] {
  animation: 1.5s cubic-bezier(.25, 1, .30, 1) diamond-in-hesitate both;


}

/* Estilos para la sección de imágenes y paneles */
        .image-section {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 50px;
        

        }

        .image-container {
            position: relative;
            width: 200px;
            height: 200px;
            overflow: hidden;
            border: 1px solid #ccc;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            transition: all 0.3s ease;
        }

        .image-container img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .image-container:hover img {
            transform: scale(1.1);
        }

        .info {
            position: absolute;
            bottom: 0;
            left: 0;
            width: 100%;
            background-color: rgba(0, 0, 0, 0.8);
            color: white;
            text-align: center;
            padding: 8px;
            box-sizing: border-box;
            transition: all 0.3s ease;
            transform: translateY(100%);
        }

        .image-container:hover .info {
            transform: translateY(0);
        }

.navbar {
    background-color: #425413;
            padding: 10px;
            position: fixed; /* Fija la barra de navegación en la parte superior */
            top: 0;
            width: 100%;
            z-index: 1000; /* Asegura que la barra de navegación esté por encima de otros elementos */
            box-sizing: border-box; /* Asegura que el padding se incluya en el ancho */
}

.nav-list {
    list-style-type: none;
    display: flex;
    align-items: center;
    margin: 0;
    padding: 0;
}

.nav-item {
    margin-right: 20px;
    position: relative;
}

.nav-item a {
    color: white;
    text-decoration: none;
    padding: 8px 16px;
    display: block;
}

.nav-item a:hover {
    background-color: #4e6311;
    border-radius: 4px;
}

.search-item {
    display: flex;
    align-items: center;
    margin-left: auto;
}

.search-input {
    border: none;
    outline: none;
    padding: 8px;
    border-radius: 25px 0 0 25px;
    width: 200px;
}

.search-button {
    border: none;
    background-color: #74940a;
    color: white;
    padding: 8px 16px;
    border-radius: 0 25px 25px 0;
    cursor: pointer;
    transition: background-color 0.3s;
}

.search-button:hover {
    background-color: #0056b3;
}

.dropdown {
    position: relative;
    display: inline-block;
}

.dropdown-content {
    display: none;
    position: absolute;
    background-color: #f9f9f9;
    min-width: 160px;
    box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
    z-index: 1;
}

.dropdown-content a {
    color: black;
    padding: 12px 16px;
    text-decoration: none;
    display: block;
}

.dropdown-content a:hover {
    background-color: #f1f1f1;
}

.dropdown:hover .dropdown-content {
    display: block;
}

.dropdown:hover .dropbtn {
    background-color: #575757;
    border-radius: 4px;
}

.image-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px;
}

.image-container img {
    margin: 100px;
    width: 200px;
    height: 150px;
}




.comentarios {
    background-color: #a34532;
   padding: 10px;
     display: inline-block; /*  el borde se ajuste al tamaño del contenido */
     margin: 0 auto;
  }


 .container {
        display: flex;
        justify-content: flex-end;
              gap: 20
              0px; /* Espacio entre los elementos */

    }

    .informa {
        background-image: linear-gradient(to left, #c3553f, #fcf5f4);
        padding: 10px;
    }

footer {
  background-color: #3d1912;
  padding: 20px;
  color: #fcf5f4;
}

footer .container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

footer .row {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
}

footer .pie {
  flex-basis: 33.33%;
  margin: 20px;
}



footer ul {
  list-style: none;

}

footer li {
  margin-bottom: 10px;
}

footer a {
  color: #e59484;
  text-decoration: none;
}

footer a:hover {
  color: #f0bcb1;
}

footer .copyright {
  font-size: 14px;
  color: #d3614a;
  text-align: center;
}

    </style>

<section>

     <img src="https://www.gaceta.unam.mx/wp-content/uploads/2019/10/191014-com4-des-f1-donacion-organis.jpg" title="Desayuno" >
    <img src="https://miguelkhourycom.files.wordpress.com/2022/09/mac-1-26-de-septiembre.jpg"  title="carne">
    <img src="https://img.freepik.com/vector-premium/ilustracion-plana-dia-mundial-donacion-organos-manos-sosteniendo-corazon_23-2149481675.jpg" title="Ensalada">
    <img src="https://img.freepik.com/vector-gratis/ilustracion-plana-dia-mundial-donacion-organos-manos-que-muestran-corazon_23-2149478062.jpg" title="Postres">
</section>

<hr style="border: 8px solid #9c3939;">


<section class="image-section"> 
        <div class="image-container" transition-style="in:diamond:hesitate">
            <a href="pag.html" target="self"> 
                <img src="https://img.freepik.com/vector-premium/donacion-organos-manos-sostienen-pulmones-corazon-higado-donante-trasplante-ayuda-voluntaria-paciente_284092-1082.jpg" alt="Acerca de">
            </a>
            <div class="info">Acerca de la información de órganos tenemos limitada información "acerca de"</div>
        </div>

        <div class="image-container" transition-style="in:diamond:hesitate">
        <a href="casos.html">
            <img src="https://www.organdonor.gov/sites/default/files/organ-donor/learn/statistics/stat-04.png" alt="Imagen 2">
            <div class="info">Casos de la donación de órganos</div>
            </a>
        </div>

        <div class="image-container" transition-style="in:diamond:hesitate">
            <a href="apo.html">
            <img src="https://cdn-icons-png.flaticon.com/512/3045/3045268.png" alt="Imagen 3">
            </a>
            <div class="info">Aportación</div>
        </div>

        <div class="image-container" transition-style="in:diamond:hesitate">
            <a href="contatctos.html" target="self">
            <img src="https://cdn-icons-png.freepik.com/512/4312/4312801.png" alt="Imagen 4">
            </a>
            <div class="info">Sugerencia y contacto</div>
        </div>

       
 

    <p style="text-align: center;"> ---------------------------------------------------
<mark>Pikarle en la imagen para que se vaya directo a otra pag  </mark>

------------------------------------------------------- </p>

    <pre>
        <div class="container">
        <blockquote class="tiktok-embed" cite="https://www.tiktok.com/@ricksanimacion/video/7283133674629909766" data-video-id="7283133674629909766" style="max-width: 605px;min-width: 325px;" > <section> <a target="_blank" title="@ricksanimacion" href="https://www.tiktok.com/@ricksanimacion?refer=embed">@ricksanimacion</a> Hoy se conmemora en México el &#34;Día Nacional de la donación y transplante de Órganos y Tejidos&#34; , una fecha que nos recuerda que en algún momento nos puede servir o podemos ser partícipes de ayudar y salvar una vida o que nos salven la vida .... <a title="donacion" target="_blank" href="https://www.tiktok.com/tag/donacion?refer=embed">#donacion</a> <a title="donacionesconamor❤️" target="_blank" href="https://www.tiktok.com/tag/donacionesconamor%E2%9D%A4%EF%B8%8F?refer=embed">#donacionesconamor❤️</a> <a title="corazon" target="_blank" href="https://www.tiktok.com/tag/corazon?refer=embed">#corazon</a> <a title="desfile" target="_blank" href="https://www.tiktok.com/tag/desfile?refer=embed">#desfile</a> <a title="dianacionaldeladonaciondeorganos" target="_blank" href="https://www.tiktok.com/tag/dianacionaldeladonaciondeorganos?refer=embed">#dianacionaldeladonaciondeorganos</a> <a title="animaciondigital" target="_blank" href="https://www.tiktok.com/tag/animaciondigital?refer=embed">#animaciondigital</a> <a title="infografiacreativa" target="_blank" href="https://www.tiktok.com/tag/infografiacreativa?refer=embed">#infografiacreativa</a> <a title="videoanimado" target="_blank" href="https://www.tiktok.com/tag/videoanimado?refer=embed">#videoanimado</a> <a title="historiaanimada" target="_blank" href="https://www.tiktok.com/tag/historiaanimada?refer=embed">#historiaanimada</a> <a title="contenidoeducativo" target="_blank" href="https://www.tiktok.com/tag/contenidoeducativo?refer=embed">#contenidoeducativo</a> <a title="videotiktok" target="_blank" href="https://www.tiktok.com/tag/videotiktok?refer=embed">#videotiktok</a> <a title="artistadigital" target="_blank" href="https://www.tiktok.com/tag/artistadigital?refer=embed">#artistadigital</a> <a title="digitalartist" target="_blank" href="https://www.tiktok.com/tag/digitalartist?refer=embed">#digitalartist</a> <a title="animacion2d" target="_blank" href="https://www.tiktok.com/tag/animacion2d?refer=embed">#animacion2d</a> <a title="animaciones" target="_blank" href="https://www.tiktok.com/tag/animaciones?refer=embed">#animaciones</a> <a title="animacionesinfantiles" target="_blank" href="https://www.tiktok.com/tag/animacionesinfantiles?refer=embed">#animacionesinfantiles</a> <a title="2danimationart" target="_blank" href="https://www.tiktok.com/tag/2danimationart?refer=embed">#2danimationart</a> <a title="organoshumanos" target="_blank" href="https://www.tiktok.com/tag/organoshumanos?refer=embed">#organoshumanos</a> <a title="character2d" target="_blank" href="https://www.tiktok.com/tag/character2d?refer=embed">#character2d</a> <a title="efemerides" target="_blank" href="https://www.tiktok.com/tag/efemerides?refer=embed">#efemerides</a> <a title="celebracionmexico" target="_blank" href="https://www.tiktok.com/tag/celebracionmexico?refer=embed">#celebracionmexico</a> <a target="_blank" title="♬ sonido original - Rick_uv" href="https://www.tiktok.com/music/sonido-original-7283133705068350214?refer=embed">♬ sonido original - Rick_uv</a> </section> </blockquote> <script async src="https://www.tiktok.com/embed.js"></script>

    <div class="informa">
  <div  transition-style="in:diamond:hesitate" style="font-family: cursive;  text-align: center;">
<h1> Informacion  </h1>
</div>



    <h2>Donación de Órganos</h2>
    La donación de órganos es el proceso de donar órganos sanos de una persona para 
     ser trasplantados a otra persona que los necesita.
      Este acto puede salvar y mejorar muchas vidas.

    <h3>Beneficios de la Donación de Órganos</h3>
    <ul>
        <li>Salva vidas: Un solo donante puede salvar hasta ocho vidas.</li>
        <li>Mejora la calidad de vida: Los receptores pueden vivir más y mejor.</li>
        <li>Ayuda a la ciencia: La donación también puede apoyar la investigación médica.</li>
    </ul>

    <h3>Cómo Convertirse en Donante</h3>
    Para ser donante de órganos, puedes registrarte en el sistema 
    de donación de tu país  y asegurarte de que tu
     familia conoce tu decisión.
</div>
</pre>
<footer>
    </div>
  <div class="container" >
    <div class="comentarios" >


    <h2>Deja tu comentario</h2>
    <form border="6" align="center" style="border-collapse: collapse; width: 50%;">
        <label for="nombre">Nombre:</label><br>
        <input type="text" id="nombre" name="nombre" required><br><br>

        <label for="correo">Correo electrónico:</label><br>
        <input type="email" id="correo" name="correo" required><br><br>

        <label for="comentario">Comentario:</label><br>
        <textarea id="comentario" name="comentario" rows="4" cols="50" required></textarea><br><br>

                <!-- raadio botones --> 



        <label for="calificacion">¿Cómo calificarías tu experiencia?</label><br>
        <input type="radio" id="bien" name="calificacion" value="bien" required>
        <label for="bien">Bien</label><br>
        <input type="radio" id="regular" name="calificacion" value="regular">
        <label for="regular">Regular</label><br>
        <input type="radio" id="malo" name="calificacion" value="malo">
        <label for="malo">Malo</label><br>
        <input type="radio" id="pesimo" name="calificacion" value="pesimo">
        <label for="pesimo">Pésimo</label><br><br>

        <!-- checbox --> 

         <label for="no_gusto">¿Qué aspectos no te gustaron?</label><br>
        <div class="checkbox-group">
            <input type="checkbox" id="diseno" name="nogusto" value="diseno">
            <label for="diseno">Diseño</label>

            <input type="checkbox" id="falta_informacion" name="nogusto" value="falta_informacion">
            <label for="falta">Falta de información</label>



            </select><br><br>


        <input type="submit" value="Enviar">

    </form>
</div>
</div>

    <div class="row">
      <div class="pie">
        <h4>Acerca de nosotros</h4>
        <p>Somos una organización sin fines de lucro dedicada a la donacion de organos</p>
      </div>
      <div class="pie">
        <h4>Enlaces útiles</h4>
        <ul>
          <li><a href="#">Inicio</a></li>
          <li><a href="#">Quienes somos</a></li>
          <li><a href="#">Contacto</a></li>
        </ul>

      </div>
      <div class="pie">
        <h4>Redes sociales</h4>
        <ul>
          <li><img src="   https://cdn-icons-png.flaticon.com/512/733/733603.png "  style=" width: 20px; height: 20px;"><a href="#" target="_blank"><i class="fab fa-facebook-f"></i> Facebook</a></li>
          <li><img src="   https://cdn-icons-png.flaticon.com/512/25/25347.png " style=" width: 20px; height: 20px;"><a href="#" target="_blank"><i class="fab fa-twitter"></i> Twitter</a></li>
          <li><img src="   https://cdn-icons-png.flaticon.com/512/1384/1384015.png " style=" width: 20px; height: 20px;"><a href="#" target="_blank"><i class="fab fa-instagram"></i> Instagram</a></li>
        </ul>
      </div>
    </div>
    <div class="row">
      <div class="col-md-12">
        <p>&copy; 2023 Organización sin fines de lucro. Todos los derechos reservados.</p>
         <img src="https://www.organdonor.gov/sites/default/files/organ-donor/home/cta-03-960x640.png" style="float: left; width: 400px; height: 300px;"> 
      </div>
    </div>
  </div>
</footer>




</body>
</html>
