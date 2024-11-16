
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Boost FPS</title>
    <style>
        /* Podstawowe ustawienia strony */
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
            color: white;
        }

        /* Tło kosmiczne */
        .background {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://img.freepik.com/darmowe-wektory/ciemne-tlo-szesciokatne-z-kolorem-gradientu_79603-1409.jpg?t=st=1731787277~exp=1731790877~hmac=60d947055e74fb446325316cd4ca4cb761bff631db59097d2ab806d7fe8a0a94&w=1060') no-repeat center center fixed; /* Tło kosmosu */
            background-size: cover;
            filter: brightness(0.6); /* Przyciemnia tło */
        }

        /* Wyśrodkowanie głównego tekstu */
        .content {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            font-size: 3.5em;
            font-weight: bold;
            color: #fff;
            background: linear-gradient(45deg, #ff007f, #7f00ff, #00d4ff);
            -webkit-background-clip: text;
            background-clip: text;
            text-shadow: 3px 3px 20px rgba(0, 0, 0, 0.7);
        }

        /* Mniejszy tekst poniżej */
        .subcontent {
            position: absolute;
            top: 70%;
            left: 50%;
            transform: translateX(-50%);
            text-align: center;
            font-size: 1.3em;
            max-width: 600px;
            line-height: 1.6;
            font-weight: normal;
            text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.5);
        }

        /* Styl przycisku */
        .download-button {
            display: inline-block;
            padding: 15px 30px;
            background-color: #ff6600;
            color: white;
            font-size: 1.5em;
            font-weight: bold;
            border-radius: 10px;
            text-decoration: none;
            margin-top: 20px;
            transition: background-color 0.3s ease;
        }

        /* Efekt hover na przycisku */
        .download-button:hover {
            background-color: #ff3300;
        }

    </style>
</head>
<body>

    <!-- Tło kosmiczne -->
    <div class="background"></div>

    <!-- Główny tekst na środku -->
    <div class="content">
        Zapraszamy Do Zainstalowania Naszego Boost FPS
    </div>

    <!-- Mniejszy tekst i przycisk -->
    <div class="subcontent">
        <p><strong>Dlaczego akurat nasz mod?</strong></p>
        <ul>
            <li>O wiele mniejsze lagi</li>
            <li>Boost FPS X3</li>
            <li>Łatwe pobieranie</li>
        </ul>
        <!-- Przycisk do pobrania -->
        <a href="https://twoja-strona-do-pobrania.com" class="download-button">Pobierz</a>
    </div>

</body>
</html>
