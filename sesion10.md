<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 

## HTML

``` html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Posicionamiento CSS</title>
</head>
<body>
    <div class="elemento1">
        <P>Diferencia entre position: absolute y position: relative:
<br>
position: relative; posiciona un elemento de acuerdo con su posición original. Si se especifican propiedades de desplazamiento (como top, bottom, left, right), el elemento se moverá en relación con su posición original.
<br>
position: absolute; posiciona un elemento en relación con su primer ancestro posicionado o el documento mismo. Si no hay un ancestro posicionado, el elemento se posicionará en relación con el documento. Los valores de desplazamiento (como top, bottom, left, right) se aplican en relación con el borde del elemento posicionado más cercano.
<br>
Uso de la propiedad z-index:
<br>
La propiedad z-index controla el orden de apilamiento de los elementos posicionados. Un valor mayor de z-index sitúa al elemento más cerca del espectador, lo que significa que estará más arriba en la pila de capas. Por lo tanto, se puede usar z-index para controlar qué elemento se superpone a los demás.
<br>
Por ejemplo:
<P>
```

``` css 
.elemento1 {
    position: relative;
    z-index: 1;
}

.elemento2 {
    position: relative;
    z-index: 2;
}
```

``` html
</div>
    <div class="elemento2">Contenido del segundo elemento</div>
    <p>En este caso, elemento2 estará encima de elemento1 en la pila de capas.
<br>
<h2>Uso de la propiedad display:<h2>
<p>
La propiedad display en CSS controla cómo se muestra un elemento en una página web. Algunos valores comunes para la propiedad display son:
<br>
 display: block; para que el elemento sea un bloque, ocupando todo el ancho disponible.
display: inline; para que el elemento se comporte como un elemento de línea, sin forzar un salto de línea después de él.
display: inline-block; para que el elemento se comporte como un elemento en línea pero permita la configuración de altura y ancho.
display: none; para ocultar completamente el elemento en la página.
Al cambiar el valor de display, puedes alterar cómo los elementos interactúan entre sí en el flujo del documento y cómo se representan en la página. <p>
</body>
</html>
```


## CSS

``` css
.elemento1 {
    width: 200px;
    height: 100px;
    background-color: lightblue;
    position: relative;
    top: 50px;
    left: 50px;
}

.elemento2 {
    width: 150px;
    height: 150px;
    background-color: lightgreen;
    position: absolute;
    top: 120px;
    left: 220px;
}

``` 




