<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4

# Actividad: Crear una tabla HTML con información sobre productos.

Escribir una tabla HTML con 10 filas que muestre información sobre productos reales. La tabla debe tener las siguientes columnas:

- Código
- Nombre
- Descripción
- Precio
- Stock
- Fecha de creación

Además, combinar celdas en la tabla con los atributos rowspan y colspan, como se muestra en la siguiente imagen.

# SOLUCIÓN...

<!DOCTYPE html>
<html>
<head>
    <title>Tabla de Productos de Computadora Modernos</title>
</head>
<body>
    <table border="1">
        <tr>
            <th rowspan="2">Código</th>
            <th rowspan="2">Nombre</th>
            <th rowspan="2">Descripción</th>
            <th rowspan="2">Precio</th>
            <th rowspan="2">Stock</th>
            <th colspan="2">Fecha de Creación</th>
        </tr>
        <tr>
            <th>Día</th>
            <th>Mes y Año</th>
        </tr>
        <tr>
            <td>101</td>
            <td>Portátil ultradelgado</td>
            <td>Portátil ligero con pantalla Full HD</td>
            <td>$999.99</td>
            <td>25</td>
            <td>15</td>
            <td>Octubre</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>102</td>
            <td>Monitor 4K</td>
            <td>Monitor de alta resolución con colores precisos</td>
            <td>$499.99</td>
            <td>10</td>
            <td>22</td>
            <td>Septiembre</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>103</td>
            <td>Ratón ergonómico</td>
            <td>Ratón diseñado para una comodidad óptima</td>
            <td>$49.99</td>
            <td>50</td>
            <td>5</td>
            <td>Noviembre</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>104</td>
            <td>Auriculares Inalámbricos</td>
            <td>Auriculares de alta calidad con cancelación de ruido</td>
            <td>$129.99</td>
            <td>30</td>
            <td>10</td>
            <td>Agosto</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>105</td>
            <td>Teclado Mecánico RGB</td>
            <td>Teclado mecánico con retroiluminación personalizable</td>
            <td>$79.99</td>
            <td>15</td>
            <td>2</td>
            <td>Julio</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>106</td>
            <td>Disco Duro Externo</td>
            <td>Almacenamiento adicional de alta capacidad</td>
            <td>$149.99</td>
            <td>20</td>
            <td>12</td>
            <td>Abril</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>107</td>
            <td>Impresora Multifunción</td>
            <td>Impresora, escáner y copiadora en un solo dispositivo</td>
            <td>$199.99</td>
            <td>12</td>
            <td>3</td>
            <td>Enero</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>108</td>
            <td>Webcam de Alta Definición</td>
            <td>Webcam para videoconferencias y transmisiones en vivo</td>
            <td>$69.99</td>
            <td>40</td>
            <td>7</td>
            <td>Marzo</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>109</td>
            <td>Router Wi-Fi 6</td>
            <td>Router de última generación para una conexión rápida</td>
            <td>$129.99</td>
            <td>18</td>
            <td>8</td>
            <td>Junio</td>
            <td>2023</td>
        </tr>
        <tr>
            <td>110</td>
            <td>Tableta Gráfica</td>
            <td>Tableta para diseñadores y artistas digitales</td>
            <td>$199.99</td>
            <td>8</td>
            <td>4</td>
            <td>Mayo</td>
            <td>2023</td>
        </tr>
    </table>
</body>
</html>



