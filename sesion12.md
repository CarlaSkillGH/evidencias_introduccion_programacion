<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 12 

## Sintaxis de HTML para la página web

``` HTML
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Evaluación de HTML y CSS</title>

    <!-- Ejercicio 2 - CSS Interno -->
    <style>

        ul {
            margin: 20px;
            padding: 10px;
            background-color: lightgray;
        }

        li {
            margin: 5px;
            padding: 5px;
            font-style: italic;
            color: blue;
        }

        table {
            margin: 30px;
            padding: 10px;
            background-color: lightyellow;
        }

        th,
        td {
            padding: 10px;
            text-align: center;
        }
    </style>

    <!-- Ejercicio 3 - CSS Externo con Selectores de Identificación -->
    <link rel="stylesheet" type="text/css" href="estilos.css">

    <!-- Ejercicio 4 - CSS Externo con Selectores de Clase y PseudoClases -->
    <link rel="stylesheet" type="text/css" href="estilos2.css">

</head>

<body>

    <!-- Ejercicio 1 - CSS Inline -->
    <div style="text-align: center; background-color: lightblue; padding: 20px; border-radius: 10px;">
        <img src="ruta_de_la_imagen" alt="Descripción de la imagen" style="width: 200px; height: 200px; border-radius: 50%;">
        <p style="color: white; font-family: Arial, sans-serif;">Texto de ejemplo en CSS inline</p>
    </div>

    <!-- Ejercicio 2 - CSS Interno -->
    <div>
        <h2>Lista de Ejemplo</h2>
        <ul>
            <li>Elemento 1</li>
            <li>Elemento 2</li>
            <li>Elemento 3</li>
        </ul>
    </div>

    <div>
        <h2>Tabla de Ejemplo</h2>
        <table>
            <thead>
                <tr>
                    <th>Encabezado 1</th>
                    <th>Encabezado 2</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Dato 1</td>
                    <td>Dato 2</td>
                </tr>
                <tr>
                    <td>Dato 3</td>
                    <td>Dato 4</td>
                </tr>
            </tbody>
        </table>
    </div>

    <!-- Ejercicio 3 - CSS Externo con Selectores de Identificación -->
    <div id="mi-selector">
        <ul>
            <li>Elemento 1</li>
            <li>Elemento 2</li>
        </ul>
        <select>
            <option value="1">Opción 1</option>
            <option value="2">Opción 2</option>
        </select>
    </div>

    <!-- Ejercicio 4 - CSS Externo con Selectores de Clase y PseudoClases -->
    <div class="mi-clase">
        <ul>
            <li>Elemento 1</li>
            <li>Elemento 2</li>
        </ul>
        <button>Botón</button>
    </div>

</body>

</html>
```
## Sintaxis de CSS para la página web

```CSS
/* CSS Externo con Selectores de Clase y PseudoClases */
/* Selectores de clase */
/* Etiquetas HTML: ul, li, button */
/* Atributos CSS: Espaciado entre palabras */
/* PseudoClases: nth-of-type(1):hover */

.mi-clase {
    word-spacing: 10px;
}

.mi-clase ul li:nth-of-type(1):hover {
    color: red;
}
```





