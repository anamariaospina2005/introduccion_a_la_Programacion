<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 

# Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa <strong> para resaltar texto importante.
- Utiliza <br> para insertar saltos de línea si es necesario.
- Agrega <span> para aplicar estilos específicos a porciones de texto.
- Emplea <i> para enfatizar o dar énfasis a palabras o frases.
- Utiliza <u> para subrayar texto cuando sea necesario.
- Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

# SOLUCIÓN...

<!DOCTYPE html>
<html>

<head>
    <title>Escandalosos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #1adae7;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body background="olga-thelavart-vS3idIiYxX0-unsplash.jpg">

    <header>
        <h1>THE BARE BEARS</h1>
        <h3>Recopilación en relación a la mítica serie de televisión "Escandalosos".</h3>
    </header>

    <section>
        <h2>
            <font color="0DF8F4">Imagenes de muestra</font>
        </h2>
        <h1> </h1>
        <p>A continuacón expondré un conjunto de imágnes en relación a los personajes de la famosa caricatura
            <strong>Escandalosos</strong> la cual fue
            parte de mi infancia y quisiera representar mediante esta página. </p>

        <h1>Imágen de muestra en relación al trío de personajes.</h1>
        <img src="https://i.pinimg.com/originals/10/34/e5/1034e52d87b89d33c01c783cfb319aa4.gif" width="400">
        <h4>ESCANDALOSOS es una comedia protagonizada por tres hermanos osos, Pardo, Panda y Polar, que intentan
            integrarse de maneras muy extrañas en la sociedad de los humanos: ya sea buscando comida, tratando de hacer
            amigos o de volverse famosos gracias a Internet.</h3>
            <h1>Oso Pardo</h1>
            <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_35 a. m. (2).png" width="400">
            <h4>Pardo se caracteriza por ser burbujeante, hiperactivo, ruidoso, hablador, alegre y optimista de los tres
                hermanos, siendo el más divertido, extrovertido y quien hace los planes.</h6>
                <h1>Oso Polar</h1>
                <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_31 a. m. (2).png" width="400">
                <h4>Polar es un oso polar antropomórfico. Su cuerpo está completamente cubierto de pelaje blanco (A
                    veces, tiene un tono muy claro de amarillo/marrón, pero como un azul más claro, un poco más que el
                    pelaje blanco de Panda). Aunque es el más joven de Los Osos, es más alto, más delgado y más fuerte
                    que sus hermanos mayores.</h6>
                    <h1>Oso Panda</h1>
                    <img src="latest (1000×1071) - Google Chrome 17_08_2023 10_01_13 a. m. (2).png" width="400">
                    <h4>Panda es el oso más inseguro de todos, ya que no confía en que las ideas de Pardo funcionen
                        bien. Es muy alegre y le encanta pasar el tiempo en su teléfono, por lo que se podría decir que
                        es un adicto, representando su adicción a esas tecnologías.</h6>
                        <img src="" width="">
                        <p>Las imágnes expuestas anteriormente expresan un conjunto de personajes de televisión que
                            hicieron parte de mi infancia. Razón por la que busco retratarlos aquí.</p>
    </section>

    <section>
        <h2>
            <font color="0DF8F4">Videos de muestra en relación a los carismáticos y emblemáticos personajes de
                caricatura.</font>
        </h2>
        <h1>Video #1 de muestra.</h1>
        <video src="¡Nuestro canal de YouTube! _ Escandalosos _ Cartoon Network (1).mp4" controls width="800"></video>
        <h1>Video #2 de muestra.</h1>
        <video src="El sueño de Panda _ Escandalosos _ Cartoon Network.mp4" controls width="800"></video>
        <p>Meidante estos videos expreso parte de las aventuras vividas por el conjunto de personajes. Relativamente es
            una breve expresión sobre aquello que se mostraba durante la proyección de los episodios cuándo aún eran
            emitidos por la televisión.</p>
    </section>

    <section>
        <h2>
            <font color="0DF8F4">Narrativas</font>
        </h2>
        <p>A continuación, adjunto un conjunto de audios dónde se narran breves experiencias del trío de personajes;
            Buscando representar un poco de sus aventuras mediante la imaginación.</p>
        <h1>Narrativa #1</h1>
        <audio src="y2mate.com - OSOS A DIETA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #2</h1>
        <audio src="y2mate.com - LA AGONÍA DE LA DIETA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #3</h1>
        <audio src="y2mate.com - EL CELULAR DE PANDA  ESCANDALOSOS.mp3" controls></audio>
        <h1>Narrativa #4</h1>
        <audio src="y2mate.com - Escandalosos Polar Le Tiene Miedo A Los Pepino XD (1).mp3" controls></audio>
        <p>Por igual, quise impregnar un conjunto de audio historias que nos expresan míticos momentos durante la serie.
        </p>

    </section>

    <section>
        <h2>
            <font color="0DF8F4">iFrames
        </h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/Qwi_0J9sZtk?si=c7uPxwqrGJW9L6s3"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/nPqaaEkIn4o?si=7sB8lkqt7ubAJZ5t"
            title="YouTube video player" frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
            allowfullscreen></iframe>
        <p>Por último, un breve retrato de un par de aventuras para dar culminado este espacio de representación y admiración hacia la serie. </p>
    </section>

    <footer>
       Ana María Ospina Duarte 
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>



