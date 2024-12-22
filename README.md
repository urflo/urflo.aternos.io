<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Uriel Sports - Noticias y todo sobre el mundo deportivo.">
    <title>Uriel Flores - Tu sitio de deportes</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }
        header {
            background-color: #2c3e50;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
            font-size: 2.5rem;
        }
        nav {
            background-color: #34495e;
            overflow: hidden;
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
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>

    <header>
        <h1>Uriel Sports</h1>
        <p>Tu sitio de noticias y entretenimiento deportivo</p>
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
            <h2>Bienvenidos a RumbiSports</h2>
            <p>En Uriel Sports encontrarás las últimas noticias, entrevistas, videos, y mucho más sobre el mundo deportivo. Desde fútbol hasta deportes extremos, tenemos todo lo que necesitas para mantenerte informado.</p>
        </div>
    </section>

    <section id="noticias">
        <div class="article">
            <h2>Últimas Noticias</h2>
            <ul>
                <li><strong>Fútbol:</strong> El FC Barcelona se corona campeón de La Liga.</li>
                <li><strong>NBA:</strong> Los Lakers vencen a los Celtics en un histórico partido.</li>
                <li><strong>Fórmula 1:</strong> Lewis Hamilton gana el Gran Premio de Mónaco.</li>
            </ul>
        </div>
    </section>

    <section id="equipos">
        <div class="article">
            <h2>Equipos y Jugadores</h2>
            <p>Aquí puedes conocer a los equipos más destacados y sus jugadores. Desde los equipos más populares en fútbol, hasta las estrellas de la NBA, MLB, y mucho más.</p>
            <ul>
                <li><strong>Real Madrid</strong> - Jugadores como Karim Benzema, Vinícius Jr.</li>
                <li><strong>Los Angeles Lakers</strong> - LeBron James, Anthony Davis.</li>
                <li><strong>Yankees de Nueva York</strong> - Aaron Judge, Gerrit Cole.</li>
            </ul>
        </div>
    </section>

    <section id="videos">
        <div class="article">
            <h2>Videos Destacados</h2>
            <p>¡¡¡SON LA MITAD MAS UNO, SON DE BOLIVIA Y PARAGUAY!!!.</p>
            <iframe width="560" height="315" src="https://youtu.be/cKSR1d1-nLw?si=5w6cAzMmtItw62MB" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
        </div>
    </section>

    <section id="contacto">
        <div class="article">
            <h2>Contacto</h2>
            <p>Si tienes alguna duda o comentario, ¡no dudes en contactarnos!</p>
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
