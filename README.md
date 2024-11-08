<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Competencias Digitales del Siglo XXI</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
        }

        /* Header Styles */
        header {
            background: url('https://via.placeholder.com/1200x600?text=Marca+de+Agua') no-repeat center center;
            background-size: cover;
            background-blend-mode: overlay;
            background-color: rgba(178, 34, 34, 0.9); /* overlay color */
            color: #ffffff;
            padding: 60px 20px;
            text-align: center;
            position: relative;
        }

        header h1 {
            font-size: 2.5em;
            margin-bottom: 10px;
            font-weight: bold;
            letter-spacing: 1px;
        }

        header p {
            font-size: 1.2em;
            font-weight: 300;
            color: #f0f0f0;
            max-width: 700px;
            margin: 0 auto;
            margin-top: 10px;
        }

        nav {
            text-align: center;
            background-color: #f8f8f8;
            padding: 15px 0;
            border-bottom: 1px solid #ddd;
        }

        nav a {
            color: #b22222;
            text-decoration: none;
            margin: 0 15px;
            font-weight: bold;
            font-size: 1.1em;
            transition: color 0.3s ease;
        }

        nav a:hover {
            color: #ff6347;
        }

        section {
            padding: 40px 20px;
            max-width: 900px;
            margin: 40px auto;
            background-color: #ffffff;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }

        h2 {
            color: #b22222;
            text-align: center;
            font-size: 1.8em;
            margin-bottom: 20px;
        }

        .image-container {
            text-align: center;
            margin: 20px 0;
        }

        .image-container img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            border: 2px solid #b22222;
        }

        p {
            line-height: 1.6;
            font-size: 1.1em;
            color: #555;
            margin-top: 10px;
            text-align: justify;
        }

        footer {
            background-color: #b22222;
            color: #ffffff;
            text-align: center;
            padding: 20px;
            margin-top: 20px;
            font-size: 1em;
        }

        .read-more {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 20px;
            background-color: #b22222;
            color: #ffffff;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }

        .read-more:hover {
            background-color: #ff6347;
        }

        .more-info {
            display: none;
            margin-top: 15px;
            background-color: #f8f8f8;
            padding: 10px;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
    </style>
    <script>
        function toggleMoreInfo(id) {
            const moreInfo = document.getElementById(id);
            if (moreInfo.style.display === "none") {
                moreInfo.style.display = "block";
            } else {
                moreInfo.style.display = "none";
            }
        }
    </script>
</head>
<body>

<header>
    <h1>Competencias Digitales del Siglo XXI</h1>
    <p>Desarrolla habilidades clave para navegar, aprender y colaborar eficazmente en el entorno digital actual.</p>
</header>

<nav>
    <a href="#manejo-informacion">Manejo de Información</a>
    <a href="#aprender-aprender">Aprender a Aprender</a>
    <a href="#comunicacion">Comunicación</a>
    <a href="#colaboracion">Colaboración</a>
    <a href="#ciudadania-digital">Ciudadanía Digital</a>
    <a href="#equipos-multiculturales">Trabajo en Equipos Multiculturales</a>
</nav>

<section id="manejo-informacion">
    <h2>Manejo de Información</h2>
    <div class="image-container">
        <img src="IM2" alt="Manejo de Información">
    </div>
    <p>El manejo de información es la habilidad para buscar, evaluar, organizar y utilizar la información de manera efectiva.</p>
    <button class="read-more" onclick="toggleMoreInfo('info1')">Leer más</button>
    <div id="info1" class="more-info">
        <p>Incluye el discernimiento entre fuentes confiables y no confiables y el uso de herramientas digitales para administrar grandes cantidades de información. Esto permite una mejor toma de decisiones y mejora la eficiencia en el trabajo académico y profesional.</p>
    </div>
</section>

<section id="aprender-aprender">
    <h2>Aprender a Aprender</h2>
    <div class="image-container">
        <img src="IM3" alt="Aprender a Aprender">
    </div>
    <p>Esta competencia se refiere a la capacidad de desarrollar estrategias de aprendizaje autónomo.</p>
    <button class="read-more" onclick="toggleMoreInfo('info2')">Leer más</button>
    <div id="info2" class="more-info">
        <p>En el contexto digital, implica adaptarse a nuevas tecnologías y utilizar recursos en línea para la mejora continua de conocimientos y habilidades. Fomenta la capacidad de autoevaluarse y ajustarse a cambios en el entorno digital.</p>
    </div>
</section>

<section id="comunicacion">
    <h2>Comunicación</h2>
    <div class="image-container">
        <img src="IM4" alt="Comunicación">
    </div>
    <p>La comunicación digital incluye la habilidad de expresarse clara y efectivamente en entornos virtuales.</p>
    <button class="read-more" onclick="toggleMoreInfo('info3')">Leer más</button>
    <div id="info3" class="more-info">
        <p>Abarca desde la redacción de correos electrónicos hasta la participación en videollamadas y el uso adecuado de redes sociales, promoviendo la interacción efectiva y profesional en el entorno digital.</p>
    </div>
</section>

<section id="colaboracion">
    <h2>Colaboración</h2>
    <div class="image-container">
        <img src="IM5" alt="Colaboración">
    </div>
    <p>La colaboración digital se refiere a la capacidad de trabajar con otros en entornos virtuales para alcanzar objetivos comunes.</p>
    <button class="read-more" onclick="toggleMoreInfo('info4')">Leer más</button>
    <div id="info4" class="more-info">
        <p>Implica el uso de herramientas en línea para la gestión de proyectos y la coordinación de tareas en equipos, facilitando el trabajo colaborativo a pesar de la distancia.</p>
    </div>
</section>

<section id="ciudadania-digital">
    <h2>Ciudadanía Digital</h2>
    <div class="image-container">
        <img src="IMG6" alt="Ciudadanía Digital">
    </div>
    <p>La ciudadanía digital es la habilidad para interactuar de manera ética, segura y responsable en el entorno digital.</p>
    <button class="read-more" onclick="toggleMoreInfo('info5')">Leer más</button>
    <div id="info5" class="more-info">
        <p>Incluye la protección de la privacidad, el respeto a los derechos y responsabilidades en línea, y la promoción de un uso positivo de la tecnología para el beneficio de la sociedad.</p>
    </div>
</section>

<section id="equipos-multiculturales">
    <h2>Trabajo en Equipos Multiculturales</h2>
    <div class="image-container">
        <img src="IM1.jpg" alt="Trabajo en Equipos Multiculturales">
    </div>
    <p>Esta competencia se refiere a la habilidad de colaborar en equipos con miembros de diferentes culturas y contextos.</p>
    <button class="read-more" onclick="toggleMoreInfo('info6')">Leer más</button>
    <div id="info6" class="more-info">
        <p>Implica flexibilidad en la comunicación y respeto hacia las diferencias culturales, con herramientas que faciliten la interacción y el entendimiento mutuo en equipos globales.</p>
    </div>
</section>

<footer>
    <p>&copy; 2024 Competencias Digitales del Siglo XXI</p>
</footer>

</body>
</html>

