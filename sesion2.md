<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


# Actividad 2:

## Creando mi primer sitio web

_Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido. Personaliza el sitio y utiliza diferentes etiquetas HTML_.

Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

### INICIO

> Pagina principal

```html
<!--By : Xeduark -->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mi primer sitio web</title>
    <meta name="description" content="mi empresa">
    <meta name="publication_date" content="2023-08-10">

</head>
<body bgcolor="#089fff">

    <!-- es mi primera pagina creada en clase -->
    <header>
        <h1>software para restaurantes</h1>
    </header>


    <nav>
        <a href="secundaria.html">acerca</a>
        <a href="opcional.html">contacto</a>
    </nav>
    <main>

        <p>Bienvenidos a mi sitio sobre empresas que desarrollen software para restaurantes </p>
        <p>Aqui encontraran informacion sobre nuestros productos y servicios </p>

    </main>
    <footer>
        <p>copyright 2023 - Jorge Muñoz</p>
        <p>xeduark@gmail.com</p>
    </footer>

</body>
</html>
```

### ACERCA

> Pagina secundaria

```html
<!--By : Xeduark-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<h1>NEW ORDER</h1>
<body bgcolor="#08d0ff">
     <!-- es mi segunda pagina creada en clase -->
     <header>
        <h1>somos una empresa que se encarga del software de restaurantes.</h1>
    </header>


    <nav>
        <a href="Principal.html">inicio</a>
        <a href="opcional.html">contacto</a>
    </nav>

    <section>

        <h2>En los primeros meses desarrollamos múltiples aplicaciones, sobre todo en áreas técnicas: simulaciones de depósitos, diseños estructurales o ingeniería química. Pero en 2019 realizamos nuestra primera aplicación empresarial, para un sector que como veremos en otras ediciones de esta serie siempre ha tenido una relación muy cercana con las nuevas tecnologías: </h2>
    <p>Fundada en 2016...</p>
    </section>

    <article>

<h3>MISION Y VISION</h3>
<p>Nuestra mision es: Desarrollar una empresa dedicada a la creación e implementación de productos y servicios de software apoyándonos permanentemente en criterios innovadores y tecnologías en evolución.

    Para lograr estos objetivos es fundamental contar con un equipo de profesionales altamente capacitados, y con la motivación y compromiso necesarios para proveer un alto valor agregado a nuestros clientes. Buscando ser reconocidos y aceptados tanto por el aporte diferencial brindado por nuestros Productos y Servicios como por nuestra Cultura empresaria, priorizamos la mejora continua desarrollándonos en un entorno profesional de negocios que asegure la evolución económica de largo plazo, en un clima de trabajo cordial que fomente la creatividad, el respeto por la ética comercial y por los valores humanos.

    Con la convicción que tanto el conocimiento y capacitad técnica como la calidad del servicio de atención al cliente son las que diferencian a las Empresas Líderes, ponemos todo el esfuerzo en mejorarlos sostenidamente.</p>
    </article>

    <footer>
        <p>copyright 2023 - Jorge Muñoz</p>
    </footer>

</body>

</html>
```

### CONTACTO
>Pagina opcional

```html
<!--By : Xeduark-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>contacto</title>
</head>
<body bgcolor="#a9fff7">

   <!-- es mi tercera pagina creada en clase -->
   <header>
    
    <h1>contacto</h1>
</header>


<nav>
    <a href="secundaria.html">acerca</a>
    <a href="Principal.html">inicio</a>   
</nav>
<main>
    <form>
        <label for="nombre">Nombre</label>
        <input type="text" id="nombre"><br>

        <label for="email">Email</label>
        <input type="email" id="email"><br>

        <label for="mensaje">Mensaje</label>
        <textarea id="mensaje"></textarea><br>

        <input type="submit" value="Enviar">
    </form>
    <aside>
        <h3>ubicación</h3>
        <p>calle A-bis #1-19c</p>
    </aside>

</main>

<footer>
    <p></p>copyright 2023 - Jorge Muñoz</p> 
</footer>

</body>

</html>
```
[Sesión 1](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion1.html)


[Sesión 3](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion3.html)






