<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Sun-hee Rafael</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #ffebee; /* Fondo rosa claro */
            color: #c62828; /* Texto rojo oscuro */
            text-align: center;
            padding: 50px;
            margin: 0;
        }
        h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }
        p {
            font-size: 1.5em;
            margin-bottom: 30px;
        }
        button {
            background-color: #c62828; /* Botón rojo */
            color: white;
            border: none;
            padding: 15px 30px;
            font-size: 1.5em;
            cursor: pointer;
            border-radius: 10px;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #b71c1c; /* Rojo más oscuro al pasar el mouse */
        }
        #respuesta {
            display: none;
            font-size: 2em;
            margin-top: 20px;
            color: #c62828;
        }
        .corazon {
            font-size: 4em;
            margin-top: 20px;
            animation: latido 1.5s infinite;
        }
        @keyframes latido {
            0% { transform: scale(1); }
            50% { transform: scale(1.2); }
            100% { transform: scale(1); }
        }
    </style>
</head>
<body>
    <h1>Para Sun-hee Rafael</h1>
    <p>Desde que llegaste a mi vida, todo tiene más color. Eres la persona más especial para mí, y hoy quiero hacerte una pregunta muy importante...</p>
    <button onclick="mostrarRespuesta()">¿Quieres ser mi San Valentín?</button>
    <p id="respuesta">¡Sun-hee Rafael, eres el amor de mi vida! 💖</p>
    <div class="corazon">❤️</div>

    <script>
        function mostrarRespuesta() {
            document.getElementById('respuesta').style.display = 'block';
            document.querySelector('.corazon').style.animation = 'none'; // Detiene la animación del corazón
            setTimeout(() => {
                document.querySelector('.corazon').style.animation = 'latido 1.5s infinite'; // Reinicia la animación
            }, 10);
        }
    </script>
</body>
</html>
