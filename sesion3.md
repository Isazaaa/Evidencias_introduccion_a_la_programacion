<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->
# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 imagenes
- 2 videos
- 4 audios
- 2 Inline frames

Utiliza encabezados para títulos en cada elemento `<h1>...<h6>`.

Crea una descripción para cada elemento utilizando párrafos `(<p>)`.

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa `<strong>` para resaltar texto importante.
- Utiliza `<br>` para insertar saltos de línea si es necesario.
- Agrega `<span>` para aplicar estilos específicos a porciones de texto.
- Emplea `<i>` para enfatizar o dar énfasis a palabras o frases.
- Utiliza `<u>` para subrayar texto cuando sea necesario.
- Considera el uso de `<div>` para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

## SOLUCIÓN    

```html
<!DOCTYPE html>
<html>

<head>
    <title>Pagina de Series</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #500307;
            color: rgb(225, 221, 221);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #cdc9c9;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(12, 12, 23);
        }

        footer {
            background-color: #0f1012;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Informacion variada sobre series</h1>
        <h3></h3>
    </header>

    <section>
        <center><h2>Sinopsis breve de series</h2></center><br>
        <hr>
        <h3>Breaking bad es una serie de televisión estadounidense creada en 2008 por Vince Gilligan. Fue emitida por la cadena AMC y protagonizada por Bryan Cranston, quien interpreta a un químico que se involucra en el mundo del tráfico de drogas para asegurar el futuro económico de su familia.</h3>
        <img src="https://tse1.explicit.bing.net/th?id=OIP.EDpsiyx-xF3WkBSBJ_dfSwHaKf&pid=Api&P=0&h=180" height="300" width="300"/><br>
        <hr>
        <h3>Skins es un drama televisivo británico que sigue las vivencias de un grupo de jóvenes en Brístol, al suroeste de Inglaterra. Se centra en las tensas vidas del grupo adolescente que viven los dos últimos años de instituto. Esta polémica serie ganó un premio BAFTA otorgado por el público y recibió una nominación a la mejor serie dramática.</h3>
        <img src= "https://cinemazworld.com/wp-content/uploads/2020/07/skins-1.jpg" height="210 "/>
        <hr>
        <h3>Monica, Rachel, Phoebe, Chandler, Ross y Joey son seis amigos treintañeros que viven en Nueva York. Juntos afrontan con humor las dificultades propias de su edad: líos amorosos, trabajo, familia y su propia convivencia.</h3>
        <img src= "https://cdn.wallpapersafari.com/36/31/fibKT8.jpg" height="260 "/>
        <hr>
        <h3> Rick and morty sigue las desventuras de un científico, Rick Sanchez, y su fácilmente influenciable nieto, Morty, quienes pasan el tiempo entre la vida doméstica y los viajes espaciales, temporales e intergalácticos.</h3>
        <img src= "https://4.bp.blogspot.com/-QBD0DHu6KXY/Wo14s8-k9mI/AAAAAAAAqY0/xaNuQiTlAk41HU7BpoHvOdCxhAChbtlTACLcBGAs/s1600/rickandmorty1.jpg" height="300"/>
        <hr>
        <h3>Peaky Blinders se centra en una familia de gánsteres de Birmingham, durante los años veinte y del ascenso de su jefe, Thomas Shelby, un mafioso que dominará toda Inglaterra, después de afrontar una terrible guerra.</h3>
        <img src="https://www.ecartelera.com/carteles-series/200/271/004_p.jpg" />
        <hr>
        <h3>The Big Bang Theory centra su argumento en las peripecias de cuatro jóvenes científicos tan inteligentes como torpes en la vida social. Trabajan en el California Institute of Technology, el célebre CalTech con sede en Pasadena. Sus rutinas están muy marcadas por su aficiones: la ciencia ficción, los comics, los videojuegos, la Tierra Media de Tolkien, los últimos adelantos en física, robótica, informática, etc.</h3>
    <img src= "https://www.icmedianet.org/wp/ndog/wp-content/uploads/2014/06/BigBangTheorySeason8.jpg" height="350" />
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre intros de series</p>
    </section>
    
    <video src ="SOUTH PARK.mp4" controls height="315"></video>
    <video src ="Kick.mp4" controls height="315"></video>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre soundtrack de series</p>
        <audio src="TLOU.mp3" controls></audio>
        <audio src="Dbz.mp3" controls></audio>
        <audio src="spiderman.mp3" controls></audio>
        <audio src="Horadeaventura.mp3" controls></audio>
        <audio src="Simpson.mp3" controls></audio>
        <audio src="Cowboy bebop.mp3" controls></audio>
    </section>

    <section>
        <iframe src="https://www.sensacine.com/series-tv/mejores/" width="900" height="800"></iframe>
        <br><br><hr><br>
        <iframe src="https://www.internetizado.com/paginas-web/donde-ver-series-online-gratis" width="900" height="800"></iframe>
    </section>
    <marquee>
    <img src= "https://i.kym-cdn.com/photos/images/newsfeed/002/289/809/9e0.jpg" height="80"/>
    </marquee>
    <footer>
        Juan Manuel Isaza Quiceno
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```




