<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Víctor Arboleda - Estudiante y Agrónomo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: white;
            display: flex;
            justify-content: center;
            padding: 0.5em;
        }
        nav a {
            color: white;
            margin: 0 1em;
            text-decoration: none;
            transition: background-color 0.3s, color 0.3s;
        }
        nav a:hover {
            background-color: #555;
            color: #fff;
        }
        main {
            padding: 2em;
        }
        h1, h2 {
            color: #333;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        form {
            display: flex;
            flex-direction: column;
            width: 300px;
            margin: 0 auto;
        }
        form label {
            margin-bottom: 0.5em;
        }
        form input, form textarea {
            margin-bottom: 1em;
            padding: 0.5em;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        form button {
            padding: 0.5em;
            color: white;
            background-color: #333;
            border: none;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        form button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Víctor Arboleda</h1>
        <nav>
            <a href="#about">Sobre mí</a>
            <a href="#research">Investigación</a>
            <a href="#experience">Experiencia</a>
            <a href="#contact">Contacto</a>
        </nav>
    </header>
    <main>
        <section id="about">
            <h2>Sobre mí</h2>
            <p>Soy un agrónomo apasionado por el uso de datos y tecnología para mejorar los resultados agrícolas y promover el cambio social y ambiental. Actualmente estudio en la Universidad EARTH y tengo un MBA de la Universidad de Cádiz.</p>
        </section>
        <section id="research">
            <h2>Investigación</h2>
            <ul>
                <li>
                    <strong>Effect of Improved Stoves on Wood Consumption, Particulate Matter and Carbon Monoxide Production in Central America</strong> (Sustainable Energy, agosto 2021)
                    <p>Este estudio analiza el impacto de las estufas mejoradas en el consumo de leña y la producción de partículas y monóxido de carbono.</p>
                    <a href="https://www.researchgate.net/publication/351653518_Effect_of_Improved_Stoves_on_Wood_Consumption_Particulate_Matter_and_Carbon_Monoxide_Production_in_Central_America">Leer más</a>
                </li>
                <li>
                    <strong>Small-Scale Regenerative Agriculture and its Effects on the Diet and Health of Peasant Communities in Belize, Honduras, and Panama</strong> (Latin American Conference of Rural Sociology, noviembre 2018)
                    <p>Investigación sobre cómo la agricultura regenerativa a pequeña escala afecta la dieta y salud de las comunidades campesinas en Belize, Honduras y Panamá.</p>
                </li>
            </ul>
        </section>
        <section id="experience">
            <h2>Experiencia</h2>
            <p>He trabajado en varios roles relacionados con la producción agrícola, análisis de datos y gestión de programas, incluyendo mi trabajo con Sustainable Harvest International y mi puesto actual como Program Assistant en The Ohio State University.</p>
        </section>
        <section id="contact">
            <h2>Contacto</h2>
            <form action="https://example.com/submit-form" method="post">
                <label for="name">Nombre:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Correo electrónico:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Mensaje:</label>
                <textarea id="message" name="message" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
    </main>
    <footer>
        <p>© 2024 Víctor Arboleda. Todos los derechos reservados.</p>
    </footer>
</body>
</html>

