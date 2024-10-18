
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis Gustos Musicales</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Arial', sans-serif;
            background-image: url(descarga.jpg); /* Imagen de fondo */
            background-size: cover;
            background-position: center;
            background-repeat: no-repeat;
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            position: relative;
            color: white;
        }

        h1 {
            font-size: 48px;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .video-container {
            margin-bottom: 20px;
        }

        .video-container iframe {
            width: 600px;
            height: 315px;
            border: none;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.5);
        }

        .music-list {
            list-style-type: none;
            padding: 0;
            font-size: 24px;
            text-align: center;
        }

        .music-list li {
            margin: 10px 0;
            text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.6);
        }

        /* GIF en la esquina de abajo izquierda */
        .gif-left {
            position: absolute;
            bottom: 10px;
            left: 10px;
            width: 100px;
        }

        /* GIF en la esquina de abajo derecha */
        .gif-right {
            position: absolute;
            bottom: 10px;
            right: 10px;
            width: 100px;
        }
    </style>
</head>
<body>
  <h1>Mis Gustos Musicales</h1>

    <div class="video-container">
        <iframe src="https://www.youtube.com/embed/fndgxPV1Deg" allowfullscreen></iframe>
    </div>
    <ul class="music-list">
        <li>K-pop</li>
        <li>Rock</li>
        <li>Salsa</li>
        <li>Pop</li>
        <li>Dancehall</li>
    </ul>

    <!-- GIF inferior izquierda -->
    <img class="gif-left" src="calamardo.gif" alt="Gif izquierda">

    <!-- GIF inferior derecha -->
    <img class="gif-right" src="gato.gif" alt="Gif derecha">

</body>
</html>
