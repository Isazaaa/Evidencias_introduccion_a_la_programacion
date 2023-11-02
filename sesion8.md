<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->
# Actividad: Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>
- Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>
- Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"
- Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"
- Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

# Solución

HTML

``` html
<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="stylesheet" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesion8</title>
</head>
<header>    
    <h1>Historia de los Videojuegos</h1>

</header>
<body bgcolor="#9fffec"></body>
<div class="contenedor"><img src="https://videojuegos.roams.es/images/post/es_ES_videogames/juegos.jpg" alt="">
</div>
<section>
    <p class="destacado">La historia de los videojuegos tiene su origen en la década de 1940 cuando, tras el fin de la Segunda Guerra Mundial, 
        las potencias vencedoras construyeron los primeros superordenadores programables como el ENIAC, de 1946.
        Los primeros intentos por implementar programas de carácter lúdico (inicialmente programas de ajedrez) no tardaron en aparecer, y se fueron repitiendo durante las siguientes décadas.
        ​ Los primeros videojuegos modernos aparecieron en la década de los 60, y desde entonces el mundo de los videojuegos no ha dejado de crecer y desarrollarse con el único límite que le ha impuesto la creatividad de los desarrolladores y la evolución tecnológica.
        ​ En los últimos años, se asiste a una era de progreso tecnológico dominada por una industria que promueve un modelo de consumo rápido donde las nuevas superproducciones quedan obsoletas en pocos meses, pero donde a la vez un grupo de personas e instituciones -conscientes del papel que los programas pioneros,
         las compañías que definieron el mercado y los grandes visionarios tuvieron en el desarrollo de dicha industria- han iniciado el estudio formal de la historia de los videojuegos.

    </p>
    <p class="grande"> En el 2000 Sony lanzó la anticipada PlayStation 2 y Sega lanzó otra consola con las mismas características técnicas de la Dreamcast,
        nada más que venia con un monitor de 14 pulgadas, un teclado, altavoces y los mismos mandos llamados Dreamcast Drivers 2000 Series CX-1.
        Microsoft entra en la industria de las consolas creando la Xbox en 2001.
        Nintendo lanzó el sucesor de la Nintendo 64, la Gamecube, y la primera Game Boy completamente nueva desde la creación de la compañía, la Game Boy Advance.
        Sega viendo que no podría competir, especialmente con una nueva máquina como la de Sony, anunció que ya no produciría hardware, convirtiéndose sólo en desarrolladora de software en 2002. </p>

    <p id="principal">
        Cada siete años, aproximadamente, se produce un nuevo ciclo generacional en videoconsolas. 2020 fue uno de esos años,
        en el cual se le dijo adiós para decir adiós a la generación de ps4 y xbox one como principales afectadas, y para dar
        la bienvenida a las sucesoras de estas exitosas máquinas de Sony y Microsoft: PlayStation 5 y Xbox Series X.
        Será la novena generación desde que este tipo de sistemas domésticos son una realidad en el mercado, 
        que estará marcada por nuevas aspiraciones tecnológicas e ideas que cambiarán, de una forma u otra, la forma que entendemos de consumir videojuegos.
    </p>
</section>
<div>
    <p>
        La competencia, PS4 y Xbox One, afronta el final de su vida útil después de más de seis años en el mercado. 
        La primera, con más de 102 millones de unidades en todo el mundo; la segunda, a falta de conocer datos más actualizados, 
        se estima que está en torno a los 50 millones de unidades despachadas.
    </p>
</div>

</html>
```

CSS

```css
header {
    background-color: black;
    border-radius: 5px;
    display: flex;
    justify-content: center;
    margin-bottom: 7px;
}

header h1 {
    color: red;
}

.contenedor {
    display: flex;
    justify-content: center;
}

.contenedor img {
    width: 500px;
    height: 400px;
    border: solid black 5px;

}

#sombras {
    box-shadow: 5px 5px 10px rgba(0, 0, 0, 3);
}

.destacado {
    color: green;
}

.grande {
    font-size: 20px;
}

#principal {
    color: rgb(199, 199, 10);
}

section p {
    color: blue;
}


div {
    color: grey;
}
```





