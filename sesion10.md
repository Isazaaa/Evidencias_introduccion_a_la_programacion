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
El valor position: relative mantiene al elemento en el flujo normal del documento y afecta su posición en relación con su posición original, mientras que position: absolute elimina al elemento del flujo normal y lo posiciona en relación con un ancestro posicionado o el cuerpo del documento, afectando la disposición de otros elementos en la página.

¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
La propiedad z-index se utiliza para controlar el orden de apilamiento de elementos posicionados. Puedes asignar un valor numérico a z-index en CSS, y los elementos con valores más altos se superpondrán a los elementos con valores más bajos. Esto te permite controlar qué elementos aparecen en la parte superior o inferior de la pila de elementos en una página web.

¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?
La propiedad display se usa para controlar cómo se muestra un elemento en una página web. Puedes asignar valores como block, inline, inline-block, none, etc., para determinar si un elemento se muestra como un bloque, una línea en el flujo de texto, una combinación de ambos o se oculta completamente. Esto afecta la disposición y presentación de elementos en la página.



