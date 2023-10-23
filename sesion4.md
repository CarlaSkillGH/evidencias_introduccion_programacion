<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 4

## Sintaxis de HTML para la página web

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tablas</title>
</head>
<body>
    <h2> Actividad de la semana 4 </h2>
    <table border="10" cellpadding="5" cellspacing="5">
        <thead>
            <tr>
                <th>Código</th>
                <th>Nombre</th>
                <th>Descripción</th>
                <th>Precio</th>
                <th>Stock</th>
                <th>Lote</th>
                <th>Imagen P1</th>
                <TH>Imagen p2</TH>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td> 008 </td>
                <td> Pan de chocolate</td>
                <td> Tradicional pan brioch relleno con nuestra especial crema de chocolate y avellanas.
                    Finalmente cubierto con una capa en fino chocolate semiamargo</td>
                <td> 21.800 COP </td>
                <td> 128 unidades </td>
                <td> 31/08/23</td>
                <td colspan="2"> <img src="CHOCOLATE.jpg" width="500" height="300" alt="Pan de chocolate"> </td>

            </tr>
            <tr>
                <td > 009 </td>
                <td > Pan de chocolate mini</td>
                <td > Tradicional pan brioch relleno con nuestra especial crema de chocolate y avellanas.
                    Finalmente cubierto con una capa en fino chocolate semiamargo</td>
                <td > 21.800 COP </td>
                <td > 128 unidades </td>
                <td > 31/08/23</td>
                <td colspan="2"> <img src=  gs://proyecto-de-desarrollo-li.appspot.com/drive-download-20231022T235350Z-001.zip width="500" height="300" alt="Pan de Chocolate mini"> </td>
            </tr>
            <tr>
                <td rowspan="2"> 011 </td>
                <td rowspan="2"> Brownie</td>
                <td > Un brownie es un bizcocho de chocolate pequeño, típico de la gastronomía de Estados Unidos. Se llama así por su color marrón oscuro, o brown en inglés. A veces se cubre con jarabe espeso de chocolate y puede llevar dentro trocitos de nueces, chocolate butterscotch o mantequilla de maní</td>
                <td rowspan="2"> 31.640 COP </td>
                <td rowspan="2"> 359 unidades </td>
                <td rowspan="2"> 31/08/23</td>
                <td colspan="2" rowspan="2"> <img src="brownieImagen.jpg" width="500" height="300"alt="Brownie"> </td>
            </tr>
            <tr>
                <td > Brownie 10 es un producto a base de chocolate (cacao o algarroba), azúcar y harina, que tiene una textura que es un cruce entre una tarta y el dulce de azúcar.</td>

            </tr>
        </tbody>

    </table>
</body>

</html>
```






