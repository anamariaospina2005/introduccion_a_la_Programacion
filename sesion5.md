<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 

# Actividad: Diseñar un formulario de pedido de un producto

Objetivo: Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

### Instrucciones:

1. Crear un nuevo documento HTML.
2. Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
3. Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
4. Utilizar las etiquetas HTML apropiados para cada campo.

# SOLUCIÓN...

<!DOCTYPE html>
<html>
<head>
    <title>Formulario de Pedido</title>
</head>
<body>
    <h1>Formulario de Pedido</h1>
    <form action="procesar_pedido.php" method="post">
        <label for="nombre_producto">Nombre del Producto:</label>
        <input type="text" id="nombre_producto" name="nombre_producto" required><br><br>

        <label for="cantidad">Cantidad:</label>
        <input type="number" id="cantidad" name="cantidad" required><br><br>

        <label for="precio_unitario">Precio Unitario:</label>
        <input type="number" step="0.01" id="precio_unitario" name="precio_unitario" required><br><br>

        <label for="precio_total">Precio Total:</label>
        <input type="number" step="0.01" id="precio_total" name="precio_total" required><br><br>

        <label for="direccion_envio">Dirección de Envío:</label>
        <textarea id="direccion_envio" name="direccion_envio" rows="4" required></textarea><br><br>

        <h2>Información de Contacto</h2>
        <label for="nombre_contacto">Nombre:</label>
        <input type="text" id="nombre_contacto" name="nombre_contacto" required><br><br>

        <label for="correo_contacto">Correo Electrónico:</label>
        <input type="email" id="correo_contacto" name="correo_contacto" required><br><br>

        <label for="telefono_contacto">Número de Teléfono:</label>
        <input type="tel" id="telefono_contacto" name="telefono_contacto" required><br><br>

        <h2>Detalles Adicionales</h2>
        <label for="metodo_pago">Método de Pago:</label>
        <select id="metodo_pago" name="metodo_pago" required>
            <option value="tarjeta_credito">Tarjeta de Crédito</option>
            <option value="paypal">PayPal</option>
            <option value="transferencia">Transferencia Bancaria</option>
        </select><br><br>

        <label for="fecha_entrega">Fecha de Entrega:</label>
        <input type="date" id="fecha_entrega" name="fecha_entrega" required><br><br>

        <label for="comentarios">Comentarios:</label>
        <textarea id="comentarios" name="comentarios" rows="4"></textarea><br><br>

        <input type="submit" value="Enviar Pedido">
    </form>
</body>
</html>


