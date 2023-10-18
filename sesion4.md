<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan.

## SOLUCIÓN

```html
<!DOCTYPE html>
<html>

<table>
    <thead>
            
<center>
    <table border="4" cellpadding="8" cellspacing="10">
</center>

<body style="background-color:#99bcdd77;">
</body>    

<tr>
    <th>Codigo</th>
    <th>Consolas de videojuegos</th>
    <th>Descripcion</th>
    <th>Precio</th>
    <th>Stock</th>
    <th>Fecha de Creacion</th>
</tr>

<tbody>
    <tr>
        <td rowspan="2">0011</td>
        <td rowspan="2">PlayStation5</td>
        <td>Las principales características de hardware de la PlayStation 5 incluyen una unidad de estado sólido
            personalizada para transmisión de datos de alta velocidad para permitir mejoras significativas en el
            rendimiento
            del almacenamiento, una GPU AMD capaz de mostrar una resolución de 4K de hasta 120 cuadros por segundo</td>
        <td rowspan="2">US$499.00</td>
        <td rowspan="2">20</td>
        <td rowspan="2">12-05-2023</td>
    </tr>
    <tr>
        <td>Esta disponible en: Blanco y negra</td>
    </tr>

    <tr>
        <td rowspan="2">0032</td>
        <td rowspan="2">Xbox Series </td>
        <td>El auténtico corazón de esta consola de videojuegos es el chip que aglutina tanto la CPU como la lógica
            gráfica,
            dos componentes que trabajan coordinadamente en el interior de un mismo circuito integrado. Aunque este SoC
            fabricado con fotolitografía ultravioleta extrema (EUV) de 7 nm implementa las microarquitecturas Zen 2 para
            la
            CPU y RDNA 2 para el procesador gráfico, no es idéntico a las soluciones de AMD que se apoyan en ellas.
            Microsoft ha confirmado que el cerebro de sus nuevas consolas incorpora a petición de sus ingenieros algunas
            modificaciones que en cierta medida lo desmarcan de los procesadores Ryzen 3000 y las nuevas Radeon RX 6000.
        </td>
        <td rowspan="2">US$499.00</td>
        <td rowspan="2">20</td>
        <td rowspan="2">18-04-2023</td>
    </tr>
    <tr>
        <td>Esta disponible en: Carbon Black y blanca </td>
    </tr>

    <tr>
        <td rowspan="2">0013</td>
        <td rowspan="2">Nintendo Switch</td>
        <td>Nintendo considera a Switch una consola híbrida. Se puede utilizar como consola de sobremesa con la unidad
            principal insertada en una estación de acoplamiento para conectarla con un televisor. Alternativamente,
            puede
            ser extraída de la base y utilizada de forma similar a una tableta a través de su pantalla táctil o colocada
            sobre una superficie gracias a su soporte plástico integrado siendo así visible por varios jugadores.</td>
        <td rowspan="2">US$297.90</td>
        <td rowspan="2">30</td>
        <td rowspan="2">29-01-2023</td>
    </tr>
    <tr>
        <td>Esta disponible en: Azul, rojo, negro y edicion pokemon espada y escudo.</td>
    </tr>
    <tr>
        <td rowspan="2">0014</td>
        <td rowspan="2">SteamDeck</td>
        <td>Steam Deck se puede usar como PC portátil o de sobremesa usando un monitor externo. Algo parecido a lo que
            ofrecen los PC portátiles, aunque con un factor forma distinto. El dispositivo está diseñada para soportar
            gran parte de la biblioteca de Steam utilizando SteamOS, un sistema operativo que estriba en un kernel
            Debian</td>
        <td rowspan="2">US$399.000</td>
        <td rowspan="2">15</td>
        <td rowspan="2">30-02-2023</td>
    </tr>
    <tr>
        <td>Esta disponible en: Negro</td>
    </tr>

    <tr>
        <td rowspan="2">0005</td>
        <td rowspan="2">Nintendo 3DS</td>
        <td>Es una videoconsola portátil de la multinacional de origen japonés, Nintendo, para videojuegos y multimedia,
            cuya atracción principal es poder mostrar gráficos en 3D sin necesidad de gafas especiales, gracias a la
            autoestereoscopia.11 La consola es retrocompatible con la Nintendo DS y con el software de DSiWare.</td>
        <td rowspan="2">US$249,99</td>
        <td rowspan="2">25</td>
        <td rowspan="2">04-07-2021</td>
    </tr>
    <tr>
        <td>Esta disponible en: Negro, blanco, turquesa, roja</td>
    </tr>
    <tr>
        <td rowspan="2">0016</td>
        <td rowspan="2">PlayStation Portable(PSP)</td>
        <td>La PSP es la consola portátil más potente desde el punto de vista técnico del mercado actual. Su CPU a 333
            MHz y
            su pantalla de 4.3 pulgadas (con una resolución de 480 x 272 píxeles) la hace ser la más completa de entre
            todas
            las de su entorno, incluyendo aquí a la Nintendo DS y a la N-Gage, que junto con la PSP, dominan el mercado
            mundial.</td>
        <td rowspan="2">US$239.00</td>
        <td rowspan="2">17</td>
        <td rowspan="2">17-03-2022</td>
    </tr>
    <tr>
        <td>Esta disponible en: Azul, blanco y negro</td>
    </tr>
    <tr>
        <td rowspan="2">0027</td>
        <td rowspan="2">Nintendo wii</td>
        <td>La característica más distintiva de la consola es su mando inalámbrico, el Control Remoto Wii, el cual puede
            ser
            usado como un dispositivo de mano con el que apuntar, además de poder detectar la aceleración de los
            movimientos
            en tres dimensiones. Otra de sus peculiaridades es lo que se ha llamado WiiConnect24, que permite recibir
            mensajes y actualizaciones a través de Internet en el modo de espera. Por ultimo, la Wii puede sincronizarse
            con
            la consola portátil Nintendo DS, lo cual permite que la consola Wii aproveche la pantalla táctil de la
            Nintendo
            DS.</td>
        <td rowspan="2">US$242.000</td>
        <td rowspan="2">28</td>
        <td rowspan="2">19-11-2021</td>
    </tr>
    <tr>
        <td>Esta disponible en: blanco, rojo, negro y turquesa</td>
    </tr>
    <tr>
        <td rowspan="2">0018</td>
        <td rowspan="2">Xbox360</td>
        <td>Como principales características técnicas, están su unidad central de procesamiento basado en un IBM PowerPC
            y su unidad de procesamiento gráfico que soporta la tecnología de Shaders Unificados.Este le permite
            alrededor de 8 horas de juego continuo sin ningún problema, ya que esta se autoapaga cuando detecta el
            calentamiento y solo volverá a encender cuando se enfríe.</td>
        <td rowspan="2">US$149.000</td>
        <td rowspan="2">15</td>
        <td rowspan="2">14-05-2022</td>
    </tr>
    <tr>
        <td>Esta disponible en: Verde, negro, blanco y rojo</td>
    </tr>
    <tr>
        <td rowspan="2">0009</td>
        <td rowspan="2">Gamecube</td>
        <td>Su principal característica fue su procesador central basado en un IBM PowerPC (tecnología previa utilizada
            en computadoras personales y portátiles), y su procesador gráfico desarrollado por ATI Technologies.
            Nintendo, por primera vez, prescindio del cartucho (ROM) como formato de almacenamiento, y adoptó un formato
            óptico propio, el Nintendo Optical Disc.</td>
        <td rowspan="2">US$109.000</td>
        <td rowspan="2">10</td>
        <td rowspan="2">14-05-2020</td>
    </tr>
    <tr>
        <td>Esta disponible en colores: Gris, morada, rojo y negro</td>
    </tr>

    <tr>
        <td rowspan="2">0020</td>
        <td rowspan="2">PlayStation4</td>
        <td>La PlayStation 4 cuenta con un procesador AMD de 8 núcleos bajo la arquitectura x86-64. Estas instrucciones
            x86-64 están diseñados para hacer más fácil el desarrollo de videojuegos en la consola de nueva generación,
            que atrae a un mayor número de desarrolladores.</td>
        <td rowspan="2">US$299.000</td>
        <td rowspan="2">40</td>
        <td rowspan="2">25-10-2022</td>
    </tr>
    <tr>
        <td>Esta disponible en colores: Negro y dorada </td>
    </tr>
</tbody>
</table>
<marquee>
<h5>Juan Manuel Isaza Quiceno</h5>
</marquee>
</html>
```





