<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->
# Actividad: Propiedades de espaciado y unidades de medida
Objetivo:

Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:

```html
<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

En el archivo CSS, agrega el siguiente código:

```css
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

Practicar el uso de las propiedades de espaciado.

Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Border: Agrega un borde de 5 píxeles de color rojo.
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Border-radius: Agrega un radio de esquina de 10 píxeles.
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}
```

Preguntas:
- ¿Qué es la propiedad margin?
- Es una propiedad CSS que controla el espacio exterior alrededor de un elemento HTML, creando márgenes entre elelemento y otros elementos cercanos.

- ¿Qué es la propiedad padding?
- Es una propiedad CSS que controla el espacio interno alrededor del contenido de un elemento HTML, creando relleno entre el contenido y el borde del elemento.

- ¿Qué es la propiedad border?
- Es una propiedad CSS que define las características del borde de un elemento HTML, como su ancho, estilo y color.

- ¿Qué es la propiedad border-radius?
- Es una propiedad CSS que define la curvatura de las esquinas de un elemento con borde, creando esquinas redondeadas en lugar de ángulos afilados.

- ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?
- Las unidades de medida comunes son píxeles (px), porcentajes (%), em (tamaño relativo al tamaño de fuente), rem (tamaño relativo al tamaño de fuente del elemento raíz), y otras como cm, mm, in, pt y pc (unidades físicas) también pueden ser utilizadas en algunas propiedades de espaciado CSS.





