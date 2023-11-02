<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# Actividad: Propiedades de posicionamiento de CSS
Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, crea una estructura básica de página web con dos elementos div.
En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.
Ejemplo:


```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento de CSS</title>
  <style>
    .elemento-1 {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: red;
    }

    .elemento-2 {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: green;
    }
  </style>
</head>
<body>
  <div class="elemento-1"></div>
  <div class="elemento-2"></div>
</body>
</html>
```

Este ejemplo muestra dos elementos div posicionados de forma absoluta y relativa, respectivamente. El elemento .elemento-1 se posiciona a 100 píxeles de la parte superior y izquierda de la ventana del navegador, mientras que el elemento .elemento-2 se posiciona a 100 píxeles de su posición original en el flujo normal del documento.

Preguntas:

¿Cuál es la diferencia entre los valores position: absolute y position: relative?
- El valor position: relative mantiene al elemento en el flujo normal del documento y afecta su posición en relación con su posición original, mientras que position: absolute elimina al elemento del flujo normal y lo posiciona en relación con un ancestro posicionado o el cuerpo del documento, afectando la disposición de otros elementos en la página.

¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
- La propiedad z-index se utiliza para controlar el orden de apilamiento de elementos posicionados. Puedes asignar un valor numérico a z-index en CSS, y los elementos con valores más altos se superpondrán a los elementos con valores más bajos. Esto te permite controlar qué elementos aparecen en la parte superior o inferior de la pila de elementos en una página web.

¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?
- La propiedad display se usa para controlar cómo se muestra un elemento en una página web. Puedes asignar valores como block, inline, inline-block, none, etc., para determinar si un elemento se muestra como un bloque, una línea en el flujo de texto, una combinación de ambos o se oculta completamente. Esto afecta la disposición y presentación de elementos en la página.


# Solución

HTML

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Sesion10</title>
    <link rel="stylesheet" href="style.css" />
    
    
    <link
      href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css"
      rel="stylesheet"
      integrity="sha384-T3c6CoIi6uLrA9TneNEoa7RxnatzjcDSCmG1MXxSR1GAsXEV/Dwwykc2MPK8M2HN"
      crossorigin="anonymous"/>
  </head>

  <body>
    <h1>Prueba1</h1>
    <div class="elemento1">
      <div class="elemento2"></div>     
      <div class="elemento3"></div>
      <div class="elemento4"></div>
    </div>

  </body>
</html>
```

CSS

```css
.elemento1 {
    background-color: rgb(171, 170, 180);
    height: 250px;
    width: 250px;
    position: browser;
    top: 250px; 
    left: 2000px;
  }
  .elemento2 {
    background-color: rgb(226, 223, 26);
    height: 100px;
    width: 100px;
    position: relative;
    top: 70px;
    left: 20px;
    display: block;
  }
  .elemento3 {
    background-color: rgb(13, 17, 243);
    height: 100px;
    width: 100px;
    position: relative;
    top: 0px;
    left: 60px;
  }
  .elemento4 {
    background-color: rgb(236, 32, 32);
    height: 100px;
    width: 100px;
    position: relative;
    top: -80px;
    left: 100px;
    z-index: 3;
  }
```
