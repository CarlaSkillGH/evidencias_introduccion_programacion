<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 8 

## Sintaxis de HTML para la página web

```html 
<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="stiles.css"> 
    <title>Sirius Amadeus</title>
</head>

<body>
    <header>
        <h1>¡Hola, soy Sirius Amadeus!</h1>
    </header>

    <div>
        <p>Soy un carrocho muy jugueton</p>
        <p>Disponible para el desorden</p>
        <p>Atento para la comelona</p>
        <p>Dispuesto para el desmadris</p>

        
    </div>

        <img src="https://firebasestorage.googleapis.com/v0/b/proyecto-ma-ds.appspot.com/o/Amadeus%20(4).jpg?alt=media&token=02175d74-fcb3-4938-b956-8ff759242a66"
        alt="Imagen" id="sombras" width="250" height="300">

    <footer>
        <p>Amo el pollito 🐥</p>
    </footer>

    <section id="principal">
        <div>
            <p>Me gusta jugar con amiguitos</p>
            <p>Me aburren los abrazos</p>
        </div>
    </section>

    <section>
        <p>Y eso es todo por ahora 🐾</p>
    </section>
</body>

</html>
``` 

## Sintaxis de CSS para la página web

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

.destacado {
    color: green;
}

.grande {
    font-size: 20px;
}

#principal {
    color: yellow;
}

#sombras {
    box-shadow: 2px 2px 2px #888888;
}

section div p {
    color: gray;
}

section {
    text-align: center;
}
```




