<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 

``` html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Conceptos de CSS</title>
</head>
<body>
    <div class="ejemplo-elemento">
        <h1>Este es un ejemplo de elemento con diferentes estilos de CSS.</h1>
        <p>width: establece el ancho de un elemento.
height: establece la altura de un elemento.
margin: establece el espacio entre un elemento y sus bordes.
padding: establece el espacio entre el contenido de un elemento y sus bordes.
float: establece la posición de un elemento en el flujo del documento.
position: establece la posición absoluta o relativa de un elemento.
color: establece el color del texto.
background-color: establece el color de fondo de un elemento.
background-image: establece una imagen de fondo para un elemento.
background-repeat: controla cómo se repite la imagen de fondo.
background-position: controla la posición de la imagen de fondo.
font-family: establece la familia de fuentes de un elemento.
font-size: establece el tamaño de la fuente de un elemento.
font-weight: establece el peso de la fuente de un elemento.
font-style: establece el estilo de la fuente de un elemento.
font-variant: establece la variante de la fuente de un elemento.
text-align: establece la alineación del texto en un elemento.
text-decoration: establece el subrayado, el tachado o el texto en línea.
text-transform: establece la transformación del texto en un elemento.
letter-spacing: establece el espaciado entre letras en un elemento.
border-width: establece el ancho del borde de un elemento.
border-style: establece el estilo del borde de un elemento.
border-color: establece el color del borde de un elemento.
border-radius: establece los bordes redondeados de un elemento.</p>
    </div>

</body>
</html>
```

```css
/* width y height */
.ejemplo-elemento {
    width: 300px;
    height: 200px;
    /* margin y padding */
    margin: 20px;
    padding: 10px;
    /* float y position */
    float: left;
    position: relative;
    /* color y background-color */
    color: #ffffff;
    background-color: #3498db;
    /* background-image, background-repeat y background-position */
    background-image: url('ruta/de/imagen.jpg');
    background-repeat: no-repeat;
    background-position: center;
    /* font-family, font-size, font-weight, font-style y font-variant */
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
    font-style: italic;
    font-variant: small-caps;
    /* text-align, text-decoration y text-transform */
    text-align: center;
    text-decoration: underline;
    text-transform: uppercase;
    /* letter-spacing */
    letter-spacing: 2px;
    /* border-width, border-style, border-color y border-radius */
    border-width: 2px;
    border-style: solid;
    border-color: #e67e22;
    border-radius: 10px;
}

/* SeudoClases y SeudoElementos */
.ejemplo-elemento:hover {
    background-color: #e74c3c;
}

.ejemplo-elemento::before {
    content: "Antes del contenido: ";
    font-weight: normal;
}

.ejemplo-elemento::after {
    content: "Después del contenido.";
    font-style: normal;
}

```




