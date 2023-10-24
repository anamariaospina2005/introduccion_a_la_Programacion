<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 

# Actividad: Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

#### Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>     

Aplica los siguientes estilos usando seleccionadores de clase:

- Color verde a los elementos con la clase ".destacado"
- Tamaño de fuente grande a los elementos con la clase ".grande"

Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

Aplica los siguientes estilos usando seleccionadores descendientes:

- Color gris a los párrafos dentro de un <div>
- Centrar el contenido de la sección <section>

# SOLUCIÓN...

# HTML

<!DOCTYPE html>
<html>
<head>
    <title>Mi Página Web</title>
    <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
    <header>
        <h1>Encabezado</h1>
    </header>
    <section>
        <div>
            <p>Párrafo 1</p>
            <img src="imagen.jpg" alt="Imagen">
        </div>
        <p>Párrafo 2</p>
        <p class="destacado">Párrafo 3 con clase destacado</p>
    </section>
    <footer>
        <p class="grande">Pie de página</p>
    </footer>
</body>
</html>

# CSS

/* Selectores de etiqueta */
h1 {
    color: red;
}

p {
    color: blue;
}

img {
    border: 2px solid black;
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
    text-shadow: 2px 2px 4px gray;
}

/* Selectores descendientes */
section div p {
    color: gray;
}

section {
    text-align: center;
}
