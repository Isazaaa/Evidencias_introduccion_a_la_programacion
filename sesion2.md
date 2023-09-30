<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->

Actividad: Creando mi primer sitio web
Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

index.html
![Alt text](image.png)

about.html
![Alt text](image-1.png)

contact.html
![Alt text](image-2.png)


SOLUCIÓN

### index.html

```html
<!DOCTYPE html>
<html>
<head>
<title>Mi primer sitio web</title>
</head>
<body>
<header>
<h1><center>Sitio web</center></h1>
</header>
<body style="background-color:#E9DDDA;">
</body>
<hr>
<main>
<p><h3>Bienvendios a mi pagina web enfocado al rescate y adopcion de animales.</p>
</main>
<hr>
<nav>
<a href="about.html"><h3>Acerca de nosotros</h3></a>
<a href="contact.html "><h3>Contacto</h3></a>
</nav>
<br>

<img src="https://mundoanimalsantafe.com.ar/wp-
content/uploads/2019/03/img_5_consejos_para_la_convivencia_entre_perros_y_gatos_740

7_paso_2_600-1.jpg" width="500" height="400"/>
<footer>
<marquee><p>Copyright 2023 - Juan Isaza</p>
<p>juan.isaza@gmail.com</p></marquee>
</footer>

</body>
</html>
```

### about.html

```html
<!DOCTYPE html>
<head>
<title>Sobre Nosotros</title>
</head>
<body>
<header>
<h1> Sobre Nosotros</h1>
<body style="background-color:#E9DDDA;">
</body>
<p><h3>Somos un refugio dedicado al rescate y bienestar de animales en riesgo, dando un
acompañamiento durante la recuperacion del animal rescatado y posteriormente darlo en
adopcion.</h3></p>
</header>
<hr>
<nav>
<a href="index.html"><h2>Inicio</h2></a>
<a href="Contact.html"><h2>Contacto</h2></a>
</nav>
<hr>
<section>
<mark> <h2>Historia</h2>
</mark>
<p><h4>Fundada en el año 2018 con el fin de disminuir el abandono de los animales a través
de rescates, rehabilitación y tratamiento veterinario, fomentando a la adopcion y responsabilidad
hacia ellos.</h4></p>
<article>
<h3>Mision</h3>
<p><h4>Nuestra mision es Luchar por el bienestar y protección de los animales
rescatados en abandono y maltrato para despues darlos en adopción, garantizando un hogar
seguro.</h4>
<h3>Vision</h3>

<p><h4>Nuestra vision es expandirnos a mas lugares donde se puedan refugiar mas
animales y que mas gente tome consciencia a la adopcion y rescate de animales en riesgo.</h4>
</article>
<hr>
</section>
<footer>
<br><br>

<img src="https://www.infobae.com/new-resizer/qcCPGySGRt-
lbfIjjbjZ_iI_rQI=/1200x900/filters:format(webp):quality(85)/s3.amazonaws.com/arc-wordpress-
client-uploads/infobae-wp/wp-content/uploads/2017/08/24173415/selfie-perros-10.jpg"

width="500" height="400" />
<marquee>
<p>Copyright 2023-Juan Isaza </p>
</marquee>
</footer>

</body>
</html>
```

### contact.html

```html
<!DOCTYPE html>
<html>
<head>
<title>Contacto</title>
</head>
<body>
<header>
<h1><center>Contacto</center></h1>
</header>
<body style="background-color:#E9DDDA;">
</body>
<hr>
<main>
<form>
<label for="nombre">Nombre:</label>
<input type="text" id="nombre"><br><br>
<label for="email">Email:</label>
<input type="email" id="email"><br><br>
<label for="mensaje">Mensaje:</label>
<input type="text" id="mensaje"><br><br>
<input type="submit" value="Enviar">
</form>
<aside>
<hr>
<h1>Ubicacion</h1>
<p><h2>Calle 52 #77-77 Medellin</h2></p>
</aside>
<nav>
<a href="index.html"><h2>Incio</h2></a>

<a href="about.html"><h2>Acerca</h2></a>
</nav>
<hr>
</main>
<br>
<footer>
<marquee>
<img src="https://media.tenor.com/QaPEi-tcFXQAAAAC/gato-besando-a-la-camara.gif"
width="300" height="200"/>
<p>Copyright 2023 - Juan Isaza</p>
</marquee>
</footer>
</body>
</html>
```








