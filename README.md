<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Nombre de tu ONG</title>
    <link rel="stylesheet" href="styles.css"> <!-- Archivo CSS para estilos -->
</head>
<body>

<header>
    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
            <li><a href="#proyectos">Proyectos</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>
</header>

<section id="inicio">
    <h1>Bienvenidos a la ONG</h1>
    <p>Descripción breve de tu ONG y su misión.</p>
</section>

<section id="sobre-nosotros">
    <h2>Sobre Nosotros</h2>
    <p>Información detallada sobre la ONG y sus objetivos.</p>
</section>

<section id="proyectos">
    <h2>Nuestros Proyectos</h2>
    <p>Lista de proyectos actuales de la ONG.</p>
</section>

<section id="contacto">
    <h2>Contacto</h2>
    <p>Formulario de contacto y detalles de cómo contactar con la ONG.</p>
</section>

<footer>
    <p>Derechos de autor &copy; Año - Nombre de tu ONG.</p>
</footer>

</body>
</html>

body {
    font-family: Arial, sans-serif;
    line-height: 1.6;
    margin: 0;
    padding: 0;
    background-color: #f0f0f0; /* Color de fondo */
}

header {
    background-color: #333; /* Color de fondo del encabezado */
    color: #fff; /* Color del texto en el encabezado */
    padding: 10px 20px;
    text-align: center;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
}

nav ul li {
    display: inline;
    margin-right: 20px;
}

nav ul li a {
    color: #fff; /* Color del enlace */
    text-decoration: none;
}

section {
    padding: 50px 20px;
}

h1, h2 {
    color: #333; /* Color del título */
}

footer {
    background-color: #333; /* Color de fondo del pie de página */
    color: #fff; /* Color del texto en el pie de página */
    text-align: center;
    padding: 10px 0;
    position: absolute;
    bottom: 0;
    width: 100%;
}
