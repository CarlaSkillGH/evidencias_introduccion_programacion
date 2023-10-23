<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11

# Sintaxis de HTML

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
        <ol>
            <li>width: establece el ancho de un elemento.</li>
                <li>height: establece la altura de un elemento.</li>
                    <li>margin: establece el espacio entre un elemento y sus bordes.</li>
                    <li>padding: establece el espacio entre el contenido de un elemento y sus bordes.</li>
                    <li>float: establece la posición de un elemento en el flujo del documento.</li>
                    <li>position: establece la posición absoluta o relativa de un elemento.</li>
                    <li>color: establece el color del texto.</li>
                    <li>background-color: establece el color de fondo de un elemento.</li>
                    <li>background-image: establece una imagen de fondo para un elemento.</li>
                    <li>background-repeat: controla cómo se repite la imagen de fondo.</li>
                    <li>background-position: controla la posición de la imagen de fondo.</li>
                    <li>font-family: establece la familia de fuentes de un elemento.</li>
                    <li>font-size: establece el tamaño de la fuente de un elemento.</li>
                    <li>font-weight: establece el peso de la fuente de un elemento.</li>
                    <li>font-style: establece el estilo de la fuente de un elemento.</li>
                    <li>font-variant: establece la variante de la fuente de un elemento.</li>
                    <li>text-align: establece la alineación del texto en un elemento.</li>
                    <li>text-decoration: establece el subrayado, el tachado o el texto en línea.</li>
                    <li>text-transform: establece la transformación del texto en un elemento.</li>
                    <li>letter-spacing: establece el espaciado entre letras en un elemento.</li>
                    <li>border-width: establece el ancho del borde de un elemento.</li>
                    <li>border-style: establece el estilo del borde de un elemento.</li>
                    <li>border-color: establece el color del borde de un elemento.</li>
                    <li>border-radius: establece los bordes redondeados de un elemento.</li>
                        </div>
    </div>

</body>
</html>
```

## Sintaxis de CSS para la página web

```css
.ejemplo-elemento {
    width: 90%;
    height: 90%;
    margin: 20px;
    padding: 10px;
    float: left;
    position: relative;
    color: #ffffff;
    background-color: #3498db;
    background-image: url('ruta/de/imagen.jpg');
    background-repeat: no-repeat;
    background-position: center;
    font-family: Arial, sans-serif;
    font-size: 16px;
    font-weight: bold;
    font-style: italic;
    font-variant: small-caps;
    text-align: center;
    text-decoration: underline;
    text-transform: uppercase;
    letter-spacing: 2px;
    border-width: 2px;
    border-style: solid;
    border-color: #e67e22;
    border-radius: 10px;
}

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
