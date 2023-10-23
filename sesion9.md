<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 9 

## Sintaxis de HTML para la página web

```html
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>Propiedades de espaciado</title>
    <link rel="stylesheet" href="stiles.css">
</head>

<body>
    <div class="contenedor">
        <ol>
            <li> Propiedad margin: </li>
        </ol>
        <p> La propiedad CSS margin se utiliza para controlar el espacio alrededor de un elemento. Puede especificar
            valores para el margen superior, derecho, inferior y izquierdo individualmente, o puede usar la abreviatura
            margin para establecer todos los márgenes a la vez. El margen crea espacio fuera del borde del elemento.
        </p>
        <ol>
            <li> Propiedad padding: </li>
        </ol>
        <p> La propiedad CSS padding se utiliza para controlar el espacio entre el borde de un elemento y su contenido.
            Al igual que la propiedad margin, puede especificar valores para el relleno superior, derecho, inferior e
            izquierdo individualmente, o puede usar la abreviatura padding para establecer todos los rellenos a la vez.
            El relleno crea espacio dentro del borde del elemento. </p>
        <ol>
            <li> Propiedad border: </li>
        </ol>
        <p> La propiedad CSS border se utiliza para establecer el borde de un elemento. Puede especificar el ancho, el
            estilo y el color del borde. Puede establecer el ancho del borde en píxeles, puntos, porcentajes u otras
            unidades de longitud. Los estilos de borde comunes son sólidos, punteados, discontinuos, dobles, entre
            otros. </p>
        <ol>
            <li> Propiedad border-radius: </li>
        </ol>
        <p> La propiedad CSS border-radius se utiliza para redondear las esquinas de un elemento con borde. Se puede
            aplicar a todos los lados o a esquinas individuales utilizando valores específicos. Al aplicar un radio a
            las esquinas, se suavizan, lo que resulta en bordes redondeados en lugar de esquinas afiladas. </p>
        <ol>
    </div>
    <div class="elemento">
        <li> Unidades de medida para propiedades de espaciado: </li>
        </ol>
        <p> Se pueden utilizar varias unidades de medida para las propiedades de espaciado, como: </p>
        <ol>
            <ul> Píxeles (px): </ul>
        </ol>
        <p>Unidad de medida estática, un píxel representa un solo punto en una imagen o en una pantalla. </p>
        <ol>
            <ul> Porcentajes (%): </ul>
        </ol>
        <p> Esta unidad de medida se refiere al porcentaje del ancho del elemento contenedor. </p>
        <ol>
            <ul> Em (em): </ul>
        </ol>
        <p> Unidad de medida relativa que se basa en el tamaño de fuente del elemento. Un em es igual al tamaño de la
            fuente de ese elemento.</p>
        <ol>
            <ul> Rem (rem):</ul>
        </ol>
        <p> Similar a la unidad em, pero se refiere al tamaño de la fuente del elemento raíz del documento. </p>
        <ol>
            <ul> Unidades absolutas como cm, mm, in, pt, y pc: </ul>
        </ol>
        <p> Estas unidades representan medidas físicas fijas y no son tan comunes en el diseño web debido a su
            inflexibilidad en diferentes dispositivos. </p>
    </div>
</body>

</html>
```

## Sintaxis de CSS para la página web

```css
.contenedor {
    width: 500px;
    height: 500px;
  }
  
  .elemento {
    border-radius: 10px;
    border: 5px solid red;
    padding: 20px;
    margin: 10%;
    width: 500px;
    height: 500px;
  }
```





