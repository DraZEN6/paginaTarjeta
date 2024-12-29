
<!DOCTYPE html>
<html lang="en">
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <meta charset="UTF-8">
    <meta name="description" content="Invitación de boda de Karen y Sebas. Celebra con nosotros este momento especial.">
    <meta name="keywords" content="boda, invitación, Karen y Sebas, evento, celebración">
    <title>Boda de Sebastian & Karen</title>
    <link rel="icon" href="favicon.ico" type="image/x-icon">
    <style>
        /* General styles */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: 'Georgia', serif;
            background-color: #f8f3ee; /* Fondo claro cálido */
            color: #a67347; /* Color de texto acorde a la paleta */
            text-align: center;
        }

        .container {
            padding: 20px;
            width: 90%; /* Ocupa el 90% del ancho de la pantalla */
            max-width: 600px; /* Limita el tamaño máximo del contenedor */
            box-sizing: border-box;
            animation: fadeIn 1.5s ease-in-out;
        }

        h1 {
            font-size: 2.5rem; /* Tamaño inicial de fuente */
            color: #a67347;
            margin: 0;
        }

        p {
            font-size: 1.2rem;
            color: #5c4636;
        }

        .button {
            margin-top: 20px;
        }

        a {
            text-decoration: none;
            color: white;
            background-color: #a67347; /* Fondo cálido */
            padding: 10px 20px;
            border-radius: 5px;
            font-size: 1rem; /* Fuente adaptativa */
            transition: background-color 0.3s ease-in-out;
        }

        a:hover {
            background-color: #86563b; /* Fondo más oscuro al pasar el mouse */
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        /* Responsive design for smaller screens */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem; /* Reduce tamaño para pantallas pequeñas */
            }
            p {
                font-size: 1rem;
            }
            a {
                font-size: 0.9rem; /* Fuente más pequeña */
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 1.5rem;
            }
            p {
                font-size: 0.9rem;
            }
            .container {
                padding: 10px; /* Reduce el padding para pantallas muy pequeñas */
            }
            a {
                padding: 8px 16px;
                font-size: 0.8rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>¡Nos casamos!</h1>
        <p>Karen & Sebas</p>
        <p>01.03.2025</p>
        <div class="button">
            <a href="detalles.html">Ver tarjeta</a>
        </div>
    </div>
</body>
</html>