<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


# Actividad: 
>Aplicando estilos con selectores CSS
El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

* Encabezado `<header>`
* Tres párrafos `<p>`
* Una imagen `<img>`
* Un pie de página `<footer>`

Aplica los siguientes estilos usando selectores de etiqueta:

* Color rojo a los encabezados `<h1>`
* Color azul a los párrafos `<p>`
* Borde grueso negro a la imagen `<img>`

Aplica los siguientes estilos usando seleccionadores de clase:

* Color verde a los elementos con la clase ".destacado"
* Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

* Color amarillo al elemento con ID "#principal"
* Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

* Color gris a los párrafos dentro de un `<div>`
* Centrar el contenido de la sección `<section>`

## SOLUCIÓN

>El HTML que se necesita
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sesión8</title>
    <link rel="stylesheet" href="estilosBasicos.css" />
</head>

<body>
    <div>

        <header>
            <h1>
                SOY UN TITULO
            </h1>
        </header>
        <div id="contenido">
            <p>Soy el parrafo #1</p>
            <p>Soy el parrafo #2</p>
            <p>Soy el parrafo #3</p>
        </div>
        <img src="imagenes/spiderman" alt="spiderman" width="380" height="260" class="img-1">
        <h2 class="destacado">Color verde a los elementos con la clase DESTACADO</h2>
        <h3 class="grande">Tamaño de fuente grande a los elementos con la clase GRANDE</h3>
        <div id="cont">
            <h2 id="amarillo">Color amarillo al elemento con ID PRINCIPAL</h2>
            <img src="imagenes/goku.png" alt="Goku" width="500" height="260" id="sombras">
        </div>

        <footer>
            <section class="pie-1">
                <h2>TITULO DEL PIE DE PAGINA</h2>
                <div class="pie-2">
                    <p>Color gris a los párrafos dentro de un div</p>
                    <p>Color gris a los párrafos dentro de un div</p>
                </div>
            </section>
        </footer>
    </div>



</body>

</html>
```
>El CSS que se necesita
```css
#contenido{
    color: blue;
    text-align: center;
}

body{
background: lightgrey;
font-family: Arial, Helvetica, sans-serif;
}

header{
    background: mediumblue;
    text-align: center;
    color: red ;
}

.img-1{
    border: 20px solid black;
    
}

.destacado{
    color: green;
}
.grande{
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif;
}
.pie-1{
    background: rgb(207, 94, 94);
    text-align: center;
}
.pie-2{
    color: grey;
}
#amarillo{
    color: yellow;
}
#sombras{
    display: block;
    margin: 30px auto;
    width: 250px;
    filter: drop-shadow(5px 10px rgb(215, 230, 7));
}
#cont{
    background: green;
}
```
![Pagina web sesion8](imagenes/Captura%20de%20pantalla%202023-10-11%20195335.png)

[Sesion7](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion7.html)

[Sesion9](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion9.html)






