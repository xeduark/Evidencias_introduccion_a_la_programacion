<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


# Actividad: 
## Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5:
_Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección_

* 4 Imagenes
* 2 Videos
* 4 Audios
* 2 Inline Frame

**Utiliza encabezados para títulos en cada elemento (h1...h6)**.

Crea una descripción para cada elemento utilizando párrafos (p).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

* Usa ***`<strong>`*** para resaltar texto importante.
* Utiliza ***`<br>`*** para insertar saltos de línea si es necesario.
* Agrega ***`<span>`*** para aplicar estilos específicos a porciones de texto.
* Emplea ***`<i>`*** para enfatizar o dar énfasis a palabras o frases.
* Utiliza ***`<u>`*** para subrayar texto cuando sea necesario.
* Considera el uso de ***`<div>`*** para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

# PLANTILLA INICIAL 

> EJEMPLO
#
```html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html >
```
#

Semántica y Estructura de la Plantilla
El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

`<!DOCTYPE html>`: Esto define el tipo de documento como HTML5.

`<html>`: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

`<head>`: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque `<style>` para agregar reglas de estilo CSS.

`<title>`: Establece el título de la página en la pestaña del navegador.

`<style>`: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

`<body>`: Aquí se coloca el contenido principal visible de la página.

`<header>`: Sección de encabezado que contiene el título principal y un subtítulo.

`<h1>` y `<h3>`: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

`<section>`: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

`<h2>`: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

`<p>`: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

`<footer>`: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea `<br>`para separar las líneas de texto.

En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.
El encabezado `<header>` tiene un fondo oscuro, texto blanco y un espacio de relleno.
Cada sección `<section>` tiene un borde, un espacio de relleno y un margen inferior.
Los encabezados de nivel 1 y 3 están centrados.
Los encabezados de nivel 2 `<h2>`tienen color azul.
El pie de página `<footer>`tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.
Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.


### SOLUCION ###

```html
<!--By XeduarK-->
<!DOCTYPE html>
<html>

<head>
    <title>INSTRUMENTOS MUSICALES</title>
    <style>
        body {
            font-family: Courier;
        }

        header {
            background-color: #1508a4;
            color: rgb(245, 246, 244);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #0108e4cf;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(227, 28, 28);
        }

        footer {
            background-color: #8d081a;
            color: rgb(243, 241, 241);
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body bgcolor="#A9ABAB">

    <header>
        <h1>INSTRUMENTOS MUSICALES</h1>
        <h3> Instrumento musical es un objeto compuesto por la combinación de uno o más sistemas resonantes y medios
            para su vibración</h3>
    </header>

    <section>
        <h2>Instrumentos</h2>
        <h3>GUITARRA</h3>
        <img src="guitar.jpg" alt="">
        <p>La <strong>guitarra</strong> es uno de los instrumentos más populares del mundo, y uno de los más utilizados
            para interpretar
            todo tipo de música; es muy fácil que hayas oído música de guitarra en directo, tanto en grandes escenarios
            como en petit comité, en reuniones de amigos e incluso en acampadas.<br>El sonido dulce de la guitarra y
            su gran versatilidad la hacen muy especial.<i>¡Para conocerla más a fondo!</i>

        <p>

            <a
                href="https://www.amadeusescuelademusica.es/descubriendo-los-instrumentos-la-guitarra/#:~:text=El%20origen%20de%20la%20guitarra,este%20instrumento%20en%20Espa%C3%B1a%20posteriormente.">ir

                a</a>

    </section>
    <section>

        <h3>BATERIA</h3>
        <img src="drums.jpg" alt="">
        <p>La <strong>bateria</strong> es un conjunto de instrumentos musicales de percusión usado por muchas
            agrupaciones musicales</p>
        <br> En algunos países, el término «batería» también se refiere al músico que toca estos instrumentos, al igual
        que el término «baterista», ambos equivalentes. Este instrumento nació de la necesidad de producir
        diferentes percusiones en un solo sistema agrupado y cómodo para ser tocados simultáneamente por una sola
        persona. <i>Para saber más de este maravilloso instrumento</i>
        <p>
            <a
                href="https://es.wikipedia.org/wiki/Bater%C3%ADa_(instrumento_musical)#:~:text=El%20origen%20de%20la%20bater%C3%ADa,pero%20todos%20de%20origen%20turco">ir
                a
            </a>
    </section>
    <section>
        <h3>PIANO</h3>
        <img src="imagenes/piano.jpg" alt="">
        <p>El <strong>piano</strong> fue inventado por Bartolomeo Cristofori (1655-1731) de Italia.</p><br>Cristofori
        estaba insatisfecho
        por
        la carencia del control que los músicos tenían sobre el nivel de volumen del clavicordio. Le acreditan para
        cambiar
        hacia fuera el mecanismo que rasgar con un martillo para crear el piano moderno en el año 1709.<br>
        <br>El instrumento fue hecho primero nombrado "clavicembalo col piano e Forte" (literalmente, un clavicordio que
        puede
        tocar sonidos suaves y fuertes). Esto se acortó al nombre común ahora, "piano". <i>Conoce más sobre este
            instrumento</i>
        <p>
            <a
                href="https://mx.yamaha.com/es/products/contents/musical_instrument_guide/piano/structure/index.html#:~:text=El%20piano%20fue%20inventado%20por,moderno%20en%20el%20a%C3%B1o%201709.">ir
                a
            </a>
    </section>

    <section>
        <h3>TROMPETA</h3>
        <img src="trompeta.jpg" alt="">
        <p>Dentro de la familia de los bronces, la trompeta tiene un rol muy variado, desde tocar pocas notas hasta
            tener un papel protagónico. Cualquiera sea el caso, es un instrumento que se hace notar por su
            característico sonido, producido por un complejo mecanismo. En los videos a continuación, Maciej Wolenski,
            trompetista de la Orquesta Filarmónica de Santiago, nos invita a conocer interesantes detalles sobre la
            historia, funcionamiento e interpretación del instrumento.</p>
        <p>
            <a
                href="https://mas.municipal.cl/la-trompeta-los-instrumentos/#:~:text=Las%20primeras%20trompetas%20fueron%20encontradas,moderna%20en%20el%20siglo%20XIX.">ir
                a</a>

    </section>


    <section>
        <h2>VIDEOS DE LOS INSTRUMENTOS</h2>
        <p>Preparamos una serie de videos para que puedas conocer aún más el instrumento que te guste.</p>



        <h3><i>GUITARRA</i></h3>

        <video width="600" height="400" controls>
            <source src="guitarra.mp4">
        </video>
        <h4>En este video podemos apreciar un nivel avanzado de un guitarrista que puede servir de inspiración para
            muchos</h4>


        <h3><i>BATERIA</i></h3>
        <video width="600" height="400" controls>
            <source src="bateria.mp4">
        </video>
        <h4>En este video apreciamos un nivel avanzado de un baterista que puede servir de inspiración para muchos
        </h4>

    </section>




    <section>
        <h3><i>Te recomendamos escuchar estos audios de algunos instrumentos</i></h3>

        <h2>Guitarra Clasica</h2>
        <audio controls>
            <source src="Sonido de Guitarra Acústica  Sonidos de Instrumentos Musicales.mp3">
        </audio>

        <h2>Piano</h2>
        <audio controls>
            <source src="y2mate.com - Sonido piano.mp3">
        </audio>

        <h2>Trompeta</h2>
        <audio controls>
            <source src="Sonido de trompeta para despertar sonido de trompeta de campamento.mp3">
        </audio>
        <h2>Bateria Acustica</h2>
        <audio controls>
            <source src="Sonido de Batería  Sonidos de Instrumentos Musicales.mp3">
        </audio>


    </section>
    <section>




        <iframe aria-controls src="https://www.guitarboosters.com/aprender-a-tocar-guitarra/"></iframe>
        <p>En esta web un guitarrista experimentado nos da su apreciación, para saber como empezar con una guitarra</p>
    </section>

    <section>
        <iframe src="https://musicalprincipado.es/blog/2021/09/02/que-es-mejor-una-bateria-electronica-o-una-acustica/"></iframe>
        <p>En esta web podras ser asesorado y escojer la bateria que mas se adapte a tus preferencias</p>
    </section>

    <footer>
        Jorge Eduardo Muñoz Quintero
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
[Sesion2](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion2.html)


[Sesion4](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion4.html)





