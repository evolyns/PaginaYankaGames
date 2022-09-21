<!DOCTYPE html>
<html lang="es">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>yanka games</title>
    <link rel="stylesheet" href="/styles.css" />
    <link rel="icon" href="/Imagenes_inicio/favicon.png" />
  </head>
  <body class="fondo__bloque">
    
    <header class="header">
      <!-- <div a class="video__bloque" > -->
        <div class="icono">
          <img src="/Imagenes_inicio/icoyanka.png" alt="" width="160" />
          <!-- el icono tiene que estar a la izquierda arriba dejando un margin de 5 x 5 aprox -->
        </div>
        <!-- </div> -->
        <!-- este mensaje tiene que estar centrado por encima del video 
          entre el video y el background  -->
          <!-- <div class="header__grid"> -->
            <video a class="video__video" width="820" height="350" autoplay muted loop>
              <!-- este video tiene que estar centrado y ocupar mas de los costados
                que del alto.  -->
                <source src="/imagenes_inicio/Tres Acordes Games.mp4" />
              </video>
              <div class="mensaje__bloque">
              <h1 class="mensaje__titulo ">
                Yanka <br />
                Games
              </h1>
            </div>
            <div class="pagina__bloque__relleno" > "
            </div>

              <div class="pagina__bloque"  >
                <h2>INICIO</h2>
              </div>
          <nav>
            <!-- </div> -->
              <ul class="lista__bloque">
                <a class="lista__textos" href="index.html"><li>inicio</li></a>
                <a class="lista__textos" href="juegos.html"><li>juegos</li></a>
                <!-- contiene todo el boton menu desplegable por secciones dentro de politicas de privacidad
                y esta dentro de la barra de navegacion, el boton x default lleva a las politicas y despues esta el
            desplegable.  -->
            <div class="politicas__desplegable"> 
              <a href="politicas.html"> <li class="lista__textos">politicas</li></a>
              <!-- primer item contenedor y lleva  a ... -->
                  <div class="politicas__desplegable__opciones">
                    <a href="politicas.html#politicas__principio">Principio</a>
                        <a href="politicas.html#politicas__medio">Medio</a>
                        <a href="politicas.html#politicas__final">Final</a>
                    </div>
                    <!-- <label for="privacidad" >  
                      <select name="privacidad" id="privacidad" class="lista__textos"  >
                        <option value=""   >
                          amigos</option>
                         </select>
                     </label> -->
                   </div>
                   <a class="lista__textos" href="contacto.html"><li>contacto</li></a>
                   <a class="lista__textos" href="equipo.html"><li>equipo</li></a>
                   <!-- las listas tienen que estar a la derecha arriba de todo dejando 5 x x aprox    -->
                 </ul>
               </div>
             </nav>
             </header>
             <main>

               <div class="bloque__izquierda">
                 <div class="noticia__bloque"> 
                 <!-- Aca iria un h2 con subtitulo del ultimo juego o algun anuncio importante  -->
                 <h2 class="noticia__titulo">Ultimo juego: <br> Tres Acordes Tuki tuki tuki</h2>
                </div>
                <div class="fecha__bloque">
                  <h4 class="fecha__texto" >publicado el xx del xxxx</h4>
   </div>
 
    <div class="parrafo__bloque ">
    <p class=" parrafo__texto" >Nuestro ultimo juego, tres acordes tuki tuki tuki tiene una fecha de lanzamiento
      retrasada, ya que al parecer construct 3 aun no a actualizado su version para crear
      apk de 12. Playstore esta pidiendo api 12 y no 11 como antes, por ende el juego aun 
      no se puede subir. 
    </p>
  </div>
  <!-- <aside> -->
    <!-- <div class="imagen__derecha"> -->
      
      <img class="imagen__derecha__imagen__1  " id="item1" src="/imagenes_inicio/Primera_Imagen.png"  alt="">
      <img class="imagen__derecha__imagen__2" id="item2" src="/imagenes_inicio/Segunda_Imagen.png"  alt="">
      <img class="imagen__derecha__imagen__3" id="item3" src="/imagenes_inicio/Tercera_Imagen.png"  alt="">
      <img class="imagen__derecha__imagen__4" id="item4" src="/imagenes_inicio/Cuarta_Imagen.png"  alt="">
      
      
    </div>
  <!-- </aside> -->

</main>

<footer>
<div class="pie__bloque">
  <ul class="lista__footer">
    <li class="lista__footer__items" id="footer1"> <img src="/imagenes_inicio/icoyanka.png" width="54" height="54" alt=""> </li>
    <li class="lista__footer__items" id="footer2">Yanka games</li>
    <li class="lista__footer__items" id="footer3" ><a href="https://www.facebook.com/profile.php?id=100064145101092"><img src="/imagenes_inicio/face.png" width="64"
        height="64" alt="">
      </li>
    </a>
    <li class="lista__footer__items" id="footer4" ><a href="https://www.instagram.com/yankagames/">
      <img src="/imagenes_inicio/insta.png" width="64" height="64" alt=""> </li>
    </a>

    <li class="lista__footer__items" id="footer5" ><a href="https://play.google.com/store/apps/developer?id=Yanka+Games">
      <img src="/imagenes_inicio/playstore.png" width="64" height="64" alt="">
      </li>
    </a>
  </ul>
  <!-- <h2>Yanka Games</h2>  -->

  <!-- <p>juegos argentinos</p> -->
  <!-- <a class="pie__texto" href="://plhttpsay.google.com/store/apps/developer?id=Yanka+Games">Playstore</a>  -->
  </footer>

</body>

</html>
