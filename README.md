<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Uriel Sports - Noticias y todo sobre el mundo deportivo, perra.">
    <title>Uriel Sports - Tu sitio de deportes favorito, perra</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header, footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 20px;
        }
        nav {
            background-color: #34495e;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            display: inline-block;
        }
        nav a:hover {
            background-color: #1abc9c;
        }
        section {
            padding: 20px;
        }
        .article {
            background-color: white;
            margin-bottom: 20px;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        input[type="submit"] {
            background-color: #1abc9c;
            color: white;
            border: none;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #16a085;
        }
    </style>
</head>
<body>

    <header>
        <h1>Uriel Sports</h1>
        <p>Tu sitio de noticias y entretenimiento deportivo favorito, perra.</p>
    </header>
   
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#noticias">Noticias</a>
        <a href="#equipos">Equipos y Jugadores</a>
        <a href="#videos">Videos</a>
        <a href="#contacto">Contacto</a>
    </nav>

    <section id="inicio">
        <div class="article">
            <h2>Bienvenidos a Uriel Sports</h2>
            <p>En Uriel Sport encontrarás las últimas noticias, entrevistas, videos y mucho más sobre el mundo deportivo. Desde fútbol hasta deportes extremos, tenemos todo lo que necesitas para mantenerte informado, perra.</p>
        </div>
    </section>

    <section id="noticias">
        <div class="article">
            <h2>Últimas Noticias</h2>
            <ul>
                <li><strong>Fútbol:</strong> Estudiantes De La Plata se corona como el campeón del Trofeo De Campeones de La SuperJiJa luego de romperle el orto a Vélez 3:0 en Santiago del Estero.</li>
                <img src="estudiantes campeon.jpg" alt="Descripción de la imagen" width="300" height="200">
                <li><strong>NBA:</strong> Lamentablemente informamos que LeBron James ha fallecido debido a que comió un pancho en mal estado en la estación de Villa Luro de la línea Sarmiento.</li>
                </li><strong> Manu Ginobili dio las siguientes declaraciones sobre  LeBron James: "Ese negro pelotudo para lo unico que tiene las manos es para comer" mientras hacia gestos imitando a un mono 🐒🐒🐒
                <li><strong>Fórmula 1:</strong> Franco Colapinto chocó de nuevo, pendejo pelotudo, aprende a manejar.</li>
            </ul>
        </div>
    </section>

    <section id="equipos">
        <div class="article">
            <h2>Nuevos Fichajes</h2>
            <p>Aquí puedes conocer las transacciones destacadas de jugadores destacadas. De los equipos más populares en fútbol.</p>
            <ul>
                <li><strong>Real Madrid</strong> - Salida: Mbappé > Sarmiento de Junín 135m usd    .</li>
                <li><strong>River Plate</strong> - entrada: Messi<Inter de Miami 50 mangos y un paquete de yerba cachamate</li>
                <li><strong>Bokuka Jijuniors</strong> - Pablo Perez por 1 docena de facturas y un smart tv samsung 80' 8k HDR </li>
            </ul>
        </div>
    </section>

    <section id="videos">
        <div class="article">
            <h2>Videos Destacados</h2>
            <p>¡¡¡SON LA MITAD MÁS UNO, SON DE BOLIVIA Y PARAGUAY, BOCA QUE ASCO TE TENGO, LAVATE EL CULO CON AGUARRAAAAAAS!!! La hinchada de EL Millonario le dedica una cancion a la aficion de boca.</p>
            <iframe width="560" height="315" src="https://www.youtube.com/embed/cKSR1d1-nLw" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </section>

    <section id="contacto">
        <div class="article">
            <h2>Contacto</h2>
            <p>Si tienes alguna duda o comentario, ¡no dudes en contactarnos, perra!</p>
            <form>
                <label for="name">Nombre:</label><br>
                <input type="text" id="name" name="name" required><br><br>
                <label for="email">Correo electrónico:</label><br>
                <input type="email" id="email" name="email" required><br><br>
                <label for="message">Mensaje:</label><br>
                <textarea id="message" name="message" rows="4" required></textarea><br><br>
                <input type="submit" value="Enviar">
            </form>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Uriel Sports. Todos los derechos reservados.</p>
    </footer>

</body>
</html>
