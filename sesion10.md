<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 

# Actividad: 
### Propiedades de posicionamiento de CSS

Objetivo:

>Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

1. Crea un nuevo archivo HTML y CSS.
2. En el archivo HTML, crea una estructura básica de página web con dos elementos div.
3. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.

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

* 1 ¿Cuál es la diferencia entre los valores position: absolute y position: relative?
* 2 ¿Cómo se puede usar la propiedad z-index para controlar el orden de apilamiento de los elementos posicionados?
* 3 ¿Cómo se puede usar la propiedad display para controlar cómo se muestra un elemento en una página web?

### SOLUCIÓN

1. En position: *relative* , el elemento está posicionado Relativo a sí mismo. Sin embargo, un elemento absolutamente posicionado es relativo a su padre. Un elemento con position: *absolute* se elimina del flujo normal de documentos. Se posiciona automáticamente en el punto de inicio (top-left esquina) de su elemento padre.

2. z-index es una propiedad que se asigna a un elemento en CSS. Al darle un valor numérico mayor, el elemento se superpondrá sobre los elementos con valores z-index más bajos, controlando así el orden de apilamiento.

3. La propiedad CSS display especifica si un elemento es tratado como block or inline element y el diseño usado por sus hijos, como flow layout(Diseño de Flujo), grid(Cuadricula) o flex(Flexible)




[Sesión 9](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion9.html)


[Sesión 11](https://xeduark.github.io/Evidencias_introduccion_a_la_programacion/sesion11.html)





