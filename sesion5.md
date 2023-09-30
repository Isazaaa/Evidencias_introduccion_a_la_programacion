<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
# Actividad: Diseñar un formulario de pedido de un producto

Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

Instrucciones:

1. Crearun nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
    - Nombre del producto
    - Cantidad
    - Precio unitario
    - Precio total
    - Dirección de envío
    - Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
    - Método de pago
    - Fecha de entrega
    - Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

SOLUCÍON

```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Producto</title>
</head>
<body style = "background-color: #a1b3c577;"></body>

<body>

    <form action=""> 
    <h1>Formulario</h1>

    <div>
        <label for="idproducto">* Nombre del Producto: </label>
        <input type="text" name="producto" id="idproducto" required>
    </div>
<br>

<div>
    <label for="idcantidad">* Cantidad</label>
    <input type="number" name="cantidad" id="idcantidad" min="0" required>
</div>
 <br>

 <div>
    <label for="idprecio">* Precio Unitario</label>
    <input type="text" name="precio" placeholder="$" id="idprecio" required>
</div>
<br>

<div>
    <label for="idpreciototal">* Precio Total</label>
    <input type="text" name="preciototal" placeholder="$" id="idpreciototal" autofocus required>
</div>
<br>

<label for="iddireccion">* Direccion de envio</label>
<input type="text" name="direccion" placeholder="direccion" required>
<br>
<br>
<hr>
<h2>Informacion de Contacto</h2>
<div>
    <label for="idnombre">* Nombre completo</label>
    <input type="text" name="nombre" placeholder="nombre" id="idnombre">
</div>
<br>

<div>
    <label for="idteléfono">* Numero de teléfono</label>
    <input type="tel" name="teléfono" placeholder="telefono" id="idteléfono">
</div>
<br>

<div>
    <label for="correo_electrónico">* Correo electrónico</label>
    <input type="email" name="correo_electrónico" placeholder="correo">
</div>

<br>
<div>
    <label for="idmetpago">Método de Pago</label>
    <select name="metpago" id="idmetpago" required>
        <option value="efectivo" selected>Efectivo</option>
        <option value="credito">Targeta de Credito</option>
        <option value="debito">Targeta Debito</option>
    </select>
</div>
<br>

<div>
        <label for="fecha">Fecha de entrega</label>
        <input type="date" name="fecha" id="fecha">
</div>
<br>
<hr>
<div>
    <label for="comentariosid">Comentarios</label>
    <br>
    <textarea name="" id="" cols="50" rows="5" ></textarea>

</div>

    <div> 
        <input type="submit" value="Enviar">
        </div>
    </form>
</body>

</html>
```




