<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

```html 
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Página Web</title>
</head>
<body>
    <header>
        <h1>Encabezado</h1>
    </header>

    <div>
        <p>Primer párrafo</p>
        <p>Segundo párrafo</p>
        <p>Tercer párrafo</p>
    </div>

    <img src="ruta/de/la/imagen.jpg" alt="Imagen" id="sombras">

    <footer>
        <p>Pie de página</p>
    </footer>

    <section id="principal">
        <div>
            <p>Esto es un párrafo dentro de un div</p>
            <p>Esto es otro párrafo dentro de un div</p>
        </div>
    </section>

    <section>
        <p>Esto es un párrafo en una sección</p>
    </section>
</body>
</html>
``` 

```css 
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 3px solid black;
}

/* Selectores de clase */
.destacado {
    color: green;
}

.grande {
    font-size: 20px;
}

/* Selectores de ID */
#principal {
    color: yellow;
}

#sombras {
    box-shadow: 2px 2px 2px #888888;
}

/* Selectores descendientes */
section div p {
    color: gray;
}

section {
    text-align: center;
}
```




