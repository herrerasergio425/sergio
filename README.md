<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Página</title>
    <style>
        /* Estilos para el enlace "Saltar al contenido principal" */
        .skip-link {
            position: absolute;
            top: -40px;
            left: auto;
            background-color: #f1f1f1;
            color: #000;
            padding: 8px;
            z-index: 100;
        }

        .skip-link:focus {
            top: 20px;
        }

        /* Estilos básicos para la navegación */
        nav {
            background-color: #333;
            color: white;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav li {
            margin-right: 20px;
        }

        nav a {
            color: white;
            text-decoration: none;
        }

        /* Estilos básicos para el contenido principal (modelo de caja) */
        main {
            padding: 20px;
            margin-top: 20px;
            border: 1px solid #ccc;
            box-shadow: 2px 2px 5px #888888;
        }

        h1 {
            color: navy;
        }

        .coursera-deliverable {
            margin-top: 20px;
            font-style: italic;
            color: #777;
        }
    </style>
</head>
<body>
    <a href="#main" class="skip-link">Saltar al contenido principal</a>

    <header>
        <h1>Mi Página</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Acerca de</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <main id="main">
        <h2>Contenido Principal</h2>
        <p>Este es el contenido principal de mi sitio web. Aquí encontrarás la información más importante.</p>
        <p>He aplicado un poco de estilo usando el modelo de caja (padding, border, box-shadow) para hacerlo más atractivo.</p>
    </main>

    <div class="coursera-deliverable">Entregable de Coursera</div>

    <footer>
        <p>&copy; 2025 Mi Sitio</p>
    </footer>
</body>
</html>
