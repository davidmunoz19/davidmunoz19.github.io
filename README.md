<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DermaLuv - Tienda Dermatológica</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #1a73e8;
            color: white;
            padding: 10px 0;
            text-align: center;
        }

        header nav ul {
            list-style: none;
            padding: 0;
        }

        header nav ul li {
            display: inline;
            margin-right: 20px;
        }

        header nav ul li a {
            color: white;
            text-decoration: none;
        }

        section#home {
            background-image: url('hero-image.jpg');
            background-size: cover;
            text-align: center;
            padding: 100px 20px;
        }

        section#home h1 {
            font-size: 2.5em;
            color: white;
        }

        section#home p {
            font-size: 1.2em;
            color: white;
        }

        .btn {
            background-color: #1a73e8;
            color: white;
            padding: 10px 20px;
            text-decoration: none;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">
            <img src="logo.png" alt="DermaLuv">
        </div>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#productos">Productos</a></li>
                <li><a href="#servicios">Servicios</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <section id="home">
        <h1>Bienvenido a DermaLuv</h1>
        <p>Tu tienda dermatológica en línea</p>
        <a href="#productos" class="btn">Descubre nuestros productos</a>
    </section>
</body>
</html>
