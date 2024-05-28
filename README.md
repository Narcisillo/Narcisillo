<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sociedad de Médicos del Mañana</title>
    <link rel="stylesheet" href="styles.css"> <!-- Archivo CSS para estilos -->
</head>
<body>

<header style="background-color: #0052A5; color: #fff;">
    <div class="container">
        <h1>Sociedad de Médicos del Mañana</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#sobre-nosotros">Sobre Nosotros</a></li>
                <li><a href="#proyectos">Proyectos</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </div>
</header>

<section id="inicio" class="section">
    <div class="container">
        <h2>Inicio</h2>
        <p>Bienvenidos a la Sociedad de Médicos del Mañana, donde trabajamos para mejorar la salud y el bienestar de comunidades vulnerables.</p>
    </div>
</section>

<section id="sobre-nosotros" class="section">
    <div class="container">
        <h2>Sobre Nosotros</h2>
        <p>Nuestra misión es proporcionar acceso a servicios médicos de calidad y promover la educación en salud en El Salvador y más allá.</p>
        <p>Nuestra visión es crear un mundo donde la salud sea un derecho universal y accesible para todos, sin importar su condición social.</p>
    </div>
</section>

<section id="proyectos" class="section">
    <div class="container">
        <h2>Nuestros Proyectos</h2>
        <ul>
            <li>Clínicas móviles en comunidades rurales.</li>
            <li>Educación en salud en escuelas locales.</li>
            <li>Programas de prevención de enfermedades.</li>
        </ul>
    </div>
</section>

<section id="contacto" class="section">
    <div class="container">
        <h2>Contacto</h2>
        <p>Puedes contactarnos a través del siguiente formulario o visitando nuestras oficinas.</p>
        <form action="submit_form.php" method="post">
            <label for="nombre">Nombre:</label><br>
            <input type="text" id="nombre" name="nombre"><br>
            <label for="email">Correo Electrónico:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="mensaje">Mensaje:</label><br>
            <textarea id="mensaje" name="mensaje" rows="4"></textarea><br>
            <input type="submit" value="Enviar">
        </form>
    </div>
</section>

<footer style="background-color: #333; color: #fff;">
    <div class="container">
        <p>&copy; 2024 Sociedad de Médicos del Mañana. Todos los derechos reservados.</p>
    </div>
</footer>

</body>
</html>
