<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para mi amor</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffebee;
            color: #c62828;
            text-align: center;
            padding: 50px;
        }
        h1 {
            font-size: 3em;
        }
        button {
            background-color: #c62828;
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.5em;
            cursor: pointer;
            border-radius: 10px;
        }
        button:hover {
            background-color: #b71c1c;
        }
    </style>
</head>
<body>
    <h1>¿Quieres ser mi San Valentín?</h1>
    <p>Desde el momento en que te conocí, supe que eras alguien especial. Hoy quiero preguntarte algo importante...</p>
    <button onclick="mostrarRespuesta()">¡Haz clic aquí!</button>
    <p id="respuesta" style="display:none; font-size: 2em; margin-top: 20px;">¡Gracias por hacer de este San Valentín el más especial!</p>
    <script>
        function mostrarRespuesta() {
            document.getElementById('respuesta').style.display = 'block';
        }
    </script>
</body>
</html>
