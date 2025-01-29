<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi princesa </title>
    <style>
        body {
            background-color: #ffcccb;
            text-align: center;
            font-family: 'Arial', sans-serif;
            padding: 50px;
        }
        h1 {
            color: #ff1493;
            font-size: 3em;
        }
        p {
            color: #8b0000;
            font-size: 1.5em;
            min-height: 60px; /* Asegura que haya espacio para el texto */
        }
        img {
            border-radius: 50%;
            width: 200px;
            height: 200px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>¡Para mi Amorcito Merly!</h1>
    <p id="mensaje"></p> <!-- Aquí se mostrará el mensaje con el efecto de escritura -->
    <img src="https://i.imgur.com/2p2sfMH.jpeg" alt="Foto de nosotros">

    <!-- Cargar Typed.js desde un CDN -->
    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
        // Configuración de Typed.js
        document.addEventListener("DOMContentLoaded", function() {
            var typed = new Typed('#mensaje', {
                strings: [
                    "Solo quiero que sepas que te amo mucho y no puedo dejar de amarte",
                    "Quiero estar contigo",
                    "Te amo mucho",
                    "Quiero abrazarte",
                    "Recuerda que 520 ❤️",
	  "Enverdad eres todo para mi",
	  "Me arrepiento por no abrazarte",
                ],
                typeSpeed: 50,
                loop: true,
                startDelay: 1000, // Espera 1 segundo antes de empezar
                showCursor: true, // Muestra un cursor parpadeante
                cursorChar: '|' // Personaliza el cursor
            });
        });
    </script>
</body>
</html>
