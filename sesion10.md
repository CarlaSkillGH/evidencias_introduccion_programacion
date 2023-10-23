<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 10 

## Sintaxis de HTML

``` html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="stiles.css">
    <title>Posicionamiento CSS</title>
</head>
<body>
</div>
    <div class="elemento1">Contenido del primer elemento
    <p>En este caso, elemento2 estará encima de elemento1 en la pila de capas.
    </div>

<div class="elemento2">Contenido del segundo elemento
<h2>Uso de la propiedad display:<h2>
<p>
La propiedad display en CSS controla cómo se muestra un elemento en una página web. Algunos valores comunes para la propiedad display son:
<br>
<ol>
    <li> display: block; para que el elemento sea un bloque, ocupando todo el ancho disponible.</li>
        <li>display: inline; para que el elemento se comporte como un elemento de línea, sin forzar un salto de línea después de él.</li>
            <li>display: inline-block; para que el elemento se comporte como un elemento en línea pero permita la configuración de altura y ancho.</li>
                <li>display: none; para ocultar completamente el elemento en la página.</li>
Al cambiar el valor de display, puedes alterar cómo los elementos interactúan entre sí en el flujo del documento y cómo se representan en la página. <p>
</div>
</body>
</html>
```

## Sintaxis de CSS para la página web

``` css
.elemento1 {
    width: 70%;
    height: 100%;
    background-color: rgb(34, 164, 207);
    position: absolute;
    top: 50px;
    left: 50px;
}

.elemento2 {
    width: 70%;
    height: 80%;
    background-color: lightgreen;
    position: relative;
    top: 120px;
    left: 220px;    
}

``` 




