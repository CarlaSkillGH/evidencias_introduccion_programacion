<!-- No borrar o modificar -->
[Inicio](./index.md)

# Sesión 5 

## Sintaxis de HTML para la página web

``` html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Pedido</title>
</head>
<body>
    <h1>Formulario de Pedido</h1>
    <form action="procesar_pedido.php" method="POST">
        <label for="nombreProducto">Nombre del producto:</label>
        <input type="text" id="nombreProducto" name="nombreProducto" required><br><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br><br>

        <label for="precioUnitario">Precio unitario:</label>
        <input type="number" id="precioUnitario" name="precioUnitario" step="0.01" required><br><br>

        <label for="precioTotal">Precio total:</label>
        <input type="number" id="precioTotal" name="precioTotal" step="0.01" required><br><br>

        <label for="direccionEnvio">Dirección de envío:</label>
        <textarea id="direccionEnvio" name="direccionEnvio" rows="4" required></textarea><br><br>

        <label for="nombreContacto">Nombre de contacto:</label>
        <input type="text" id="nombreContacto" name="nombreContacto" required><br><br>

        <label for="correoElectronico">Correo electrónico:</label>
        <input type="email" id="correoElectronico" name="correoElectronico" required><br><br>

        <label for="numeroTelefono">Número de teléfono:</label>
        <input type="tel" id="numeroTelefono" name="numeroTelefono" required><br><br>

        <label for="metodoPago">Método de pago:</label>
        <select id="metodoPago" name="metodoPago">
            <option value="tarjeta">Tarjeta de crédito</option>
            <option value="efectivo">Efectivo</option>
            <option value="transferencia">Transferencia bancaria</option>
        </select><br><br>

        <label for="fechaEntrega">Fecha de entrega:</label>
        <input type="date" id="fechaEntrega" name="fechaEntrega"><br><br>

        <label for="comentarios">Comentarios:</label>
        <textarea id="comentarios" name="comentarios" rows="4"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>
</body>
</html>
```







