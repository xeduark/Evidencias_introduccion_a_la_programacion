<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


# Actividad: 
## Diseñar un formulario de pedido de un producto

**Objetivo:**

_Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto._

**Instrucciones:**

1 _Crear un nuevo documento HTML._

2 _Crear un formulario con los siguientes campos:_
* Nombre del producto
* Cantidad
* Precio unitario
* Precio total
* Dirección de envío
* Información de contacto (nombre, correo electrónico, número de teléfono)

3 _Agregar los siguientes campos relacionados al formulario:_
* Método de pago
* Fecha de entrega
* Comentarios

4 _Utilizar las etiquetas HTML apropiados para cada campo._

### SOLUCION
>Formulario en Html

```HTML CSS
<!--By Xeduark-->
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>

<body>
    <form action="">
        <header>
            <h1><i>Actividad #5: Diseñar un formulario de pedido de un producto</i></h1>
        </header>
        <div>
            <label for="idNombreDelProducto">* Nombre del producto</label>
            <input type="text" name="nombreDelProducto" id="idNombreDelProducto">
        </div>
        <br>
        <br>
        <div>
            <label for="idCantidadDelProducto">* Cantidad</label>
            <input type="number" name="cantidadDelProducto" placeholder="Seleccione una cantidad"
                id="idCantidadDelProducto">
        </div>
        <br>
        <br>
        <div>
            <label for="idPrecioUnitario">Precio unitario</label>
            <input type="number" name="precioUnitario" id="idPrecioUnitario">
        </div>
        <br>
        <br>
        <div>
            <label for="idPrecioTotal">Precio total</label>
            <input type="number" name="precioTotal" id="idPrecioTotal">
        </div>
        <br>
        <br>
        <div>
            <label for="idDireccionDeEnvio">* Direccion de envio</label>
            <input type="text" name="direccionDeEnvio" id="idDireccionDeEnvio">
        </div>
        <br>
        <br>
        <br>
        <h2><i>INFORMACION DE CONTACTO:</i></h2>
        <br>
        <br>
        <div>
            <label for="idNombre">* Nombre</label>
            <input type="text" name="nombre" id="idNombre">
        </div>
        <br>
        <br>
        <div>
            <label for="idCorreoElectronico">* Correo electronico</label>
            <input type="email" name="correoElectronico" id="idCorreoElectronico" autocomplete="address-level1">
        </div>
        <br>
        <br>
        <div>
            <label for="idTelefono">* Nombre del producto</label>
            <input type="tel" name="numeroTelefono" id="idTelefono">
        </div>
        <br>
        <br>
        <div>
            <label for="idMetodoDePago">* Metodo de pago</label>
            <input type="tex" name="metodoDePago" id="idMetodoDePago" placeholder="Otros">
            <select name="pagos" id="idpagos">
                <option value="1">Efectivo</option>
                <option value="2">Tarjetas de débito y crédito</option>
                <option value="3" selected>Transferencias bancarias</option>
            </select>
        </div>
        <br>
        <br>
        <div>
            <label for="idFechaDeEntrega">* Fecha de entrega</label>
            <input type="datetime-local" name="fechaEntrega" id="idFechaDeEntrega">
        </div>
        <br>
        <br>
        <div>
            <textarea name="comentarios" id="comentarios" placeholder="Ingrese sus sujerencias aquí" rows="10"
                cols="50"></textarea>
        </div>
        <br>
        <br>
        <div>
            <input type="submit" value="Enviar">
            <label for="enviar"></label>
        </div>


    </form>
</body>

</html>
```
[Sesion4](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion4.html)
[Sesion6](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion6.html)






