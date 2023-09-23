<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


# Actividad:
## Crear una tabla HTML con información sobre productos.
_Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas_:

* Código
* Nombre
* Descripción
* Precio
* Stock
* Fecha de creación

_Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen._

![imagen de una tabla diseñada en Html](https://firebasestorage.googleapis.com/v0/b/cesde-7fe22.appspot.com/o/IP%2FIPS4-1.png?alt=media&token=b46ee6fd-97c8-400e-af16-cc88c3819d00)

### SOLUCION
>Tabla sobre productos 


```HTML CSS
<!--By : XeduarK-->
<!DOCTYPE html>
<html lang="en">

<head>
    <title>10 GRANDES PRODUCTOS</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    table,
    th,
    td {
        border: 1px solid rgb(30, 0, 255);
        border-collapse: collapse;
        text-align: center;

    }
</style>

<body>
    <h1> PRODUCTOS </h1>
    <table border="10" align="5" cellpadding="20" cellspacing="10" valign="5">
        <thead>
            <tr>
                <th>Código</th>
                <th>Nombre</th>
                <th colspan="7">Descripción</th>
                <th>stock</th>
                <th>Precio</th>
                <th colspan="5">Fecha de creación</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td rowspan="2">001</td>
                <td rowspan="2">coca-cola</td>
                <td colspan="7">
                    <p>Aunque inicialmente esta popular bebida se creó como líquido medicinal patentado con
                        jarabe, que podría ayudar a mejorar los problemas digestivos, rápidamente The Coca-Cola Company
                        se
                        convirtió en la fábrica del producto más vendido en el mundo</p>
                </td>
                <td>1</td>
                <td>$6094</td>
                <td>1892, Atlanta, Georgia, Estados Unidos</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p>con más de 1,8 billones de unidades al día, lo que indica que dos de cada 10 personas consume
                        diariamente una botella de Coca-Cola en el mundo.</p>
                </td>
                <td>1</td>
                <td>1</td>


            </tr>
            <tr>
                <td rowspan="2">002</td>
                <td rowspan="2">Lay’s</td>
                <td colspan="7">
                    <p>Las famosas papas fritas o chips dueñas del slogan ‘a que no puedes comerte solo una’ nació en
                        Ohio, Estados Unidos en 1932</p>
                </td>
                <td>1</td>
                <td>$6400</td>
                <td>1932 en Nashville, Tenesse.</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p> Esta historia empezó en el baúl del vehículo de Herman Lay quien cruzó el sur de Estados Unidos
                        buscando vender estas chips de papas. Fue en 1965 que se unió con PepsiCo Inc para lograr vender
                        633 millones de paquetes solo en Estados Unidos, lo que llegaría a pesar más que un
                        portaaviones.</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">003</td>
                <td rowspan="2">ipad</td>
                <td colspan="7">
                    <p>La multinacional estadounidense Apple, que diseña y produce tecnología, tiene dos productos que
                        han sido de los más vendidos</p>
                </td>
                <td>1</td>
                <td>$1.520.000</td>
                <td>27 de enero de 2010</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p> En primera instancia está el iPad, que incluye dentro de un solo dispositivo las funciones de un
                        smartphone y un computador portátil pero con un tamaño medio, de mayor ligereza y pantalla
                        multi-touch.</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">004</td>
                <td rowspan="2">iPhone</td>
                <td colspan="7">
                    <p>Siguiendo con una de las marcas de celulares más conocida en el mundo, el puesto del cuarto
                        producto más vendido en la historia pertenece al iPhone.</p>
                </td>
                <td>1</td>
                <td>$6'561.990 ultima generacion.</td>
                <td>29 de junio de 2007</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p> Este invento que ya tiene el desarrollo de 10 generaciones de celulares, fue anunciado
                        públicamente por Steve Jobs, fundador de Apple Inc, durante la Macworld Conference & Expo
                        realizada el nueve de enero de 2007, y en Estados Unidos se lanzó el 29 de junio de 2007.</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">005</td>
                <td rowspan="2">Margarita (cóctel)</td>
                <td colspan="7">
                    <p>La margarita es un cóctel compuesto por tequila, triple seco y jugo de lima o limón. A menudo se
                        sirve con sal en el borde de la copa</p>
                </td>
                <td>1</td>
                <td>$8500</td>
                <td>finales de la década de 1930 o principios de la de 1940</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p> De origen Mexicano</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">006</td>
                <td rowspan="2"> Mario Bros</td>
                <td colspan="7">
                    <p>El sector de los videojuegos también tiene su puesto en la lista, y el primero en aparecer es el
                        plomero italiano más recordado en el mundo por su frase ‘It’s me, Mario’ </p>
                </td>
                <td>1</td>
                <td>$65000 aprox</td>
                <td>publicado por Nintendo en 1983</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p> Este personaje es la atracción principal del videojuego tipo arcade, que ha vendido 262 millones
                        de unidades, diseñado y elaborado por Nintendo por Shigeru Miyamoto en 1983, en donde Mario y
                        Luigi, su hermano menor, deben derrotar a sus enemigos..</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">007</td>
                <td rowspan="2">Play Station</td>
                <td colspan="7">
                    <p>Siguiendo con los videojuegos, este sexto puesto pertenece a Play Station, la más vendida con 344
                        millones de unidades vendidas desde el tres de diciembre de 1994, fecha oficial del lanzamiento.
                    </p>
                </td>
                <td>1</td>
                <td>los precios pueden variar por ser tan antigua, pero su valor comerciar deberia ser $170.000</td>
                <td>finales de 1994</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p>Esta consola tiene un diseño que es recordado por los usuarios, por su forma rectangular gris y
                        diseño compacto y ligero, un lector de CD en la parte superior y unas ranuras para las tarjetas
                        de memoria en la parte frontal.</p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">008</td>
                <td rowspan="2">Thriller </td>
                <td colspan="7">
                    <p>Este álbum lleva de nombre de una de las canciones más reconocidas del artista estadounidense
                        Michael Jackson</p>
                </td>
                <td>1</td>
                <td>US$750.000</td>
                <td>el 30 de noviembre de 1982</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p>Thriller fue el sexto de estudio del artista lanzado el 30 de noviembre de 1982 por Epic Records,
                        en donde se incluyeron músicas como post-disco, R&B, pop y rock. Este icónico álbum se grabó en
                        Los Ángeles, California con un presupuesto de US$750.000, y vendió más de 70 millones de
                        unidades. </p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">009</td>
                <td rowspan="2">
                    Harry Potter</td>
                <td colspan="7">
                    <p>Harry Potter es el nombre que recibe esta serie de novelas fantásticas creadas por J.K. Rowling,
                        en la que se cuenta la historia de Harry, un aprendiz de magia y su vida en el Colegio Hogwarts.
                    </p>
                </td>
                <td>1</td>
                <td>$164000 aprox</td>
                <td>junio de 1997</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p>Esta novela que tiene ocho títulos como la piedra filosofal, la cámara secreta, el cáliz del
                        fuego, las reliquias de la muerte y otros, tras la saga de Star Wars ha facturado US$5.000
                        millones y han vendido 450 millones de copias desde 1997. </p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
            <tr>
                <td rowspan="2">010</td>
                <td rowspan="2">Ferrari</td>
                <td colspan="7">
                    <p>Ferrari es un fabricante de automóviles superdeportivos con sede en Maranello, provincia de
                        Módena, en la región de Emilia-Romaña, Italia.</p>
                </td>
                <td>1</td>
                <td>42,2 millones de euros. Solo existen 36 unidades de este vehículo exclusivo que atesora un motor V12
                    250 GTO</td>
                <td>1947, Maranello, Italia</td>
            </tr>
            <tr>
                <td colspan="7">
                    <p>De la mano de Enzo Ferrari, la Scuderia Ferrari se funda en 1929 en Módena (Italia) para la
                        creación y producción exclusiva de automóviles para carreras. Perteneciente a la marca Alfa
                        Romeo, Enzo trabajó durante en los primeros desarrollos de diseños profesionales como el Alfa
                        Romeo Bimotore. </p>
                </td>
                <td>1</td>
                <td>1</td>
            </tr>
        </tbody>


    </table>

</body>

</html>
```
[Sesion3](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion3.html)
[Sesion5](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion5.html)





