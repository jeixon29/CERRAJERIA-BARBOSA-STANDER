<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cerrajería Barbosa</title>
    <style>
        /* Estilos generales */
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #0b0b0b;
            color: #ffffff;
        }

        a {
            text-decoration: none;
            color: #ffffff;
        }

        header {
            background-color: #0d47a1;
            padding: 20px;
            text-align: center;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
        }

        nav {
            background-color: #1a237e;
            display: flex;
            justify-content: center;
        }

        nav a {
            padding: 15px 25px;
            display: block;
            color: #ffffff;
            font-weight: bold;
        }

        nav a:hover {
            background-color: #3949ab;
        }

        section {
            padding: 60px 20px;
            max-width: 1000px;
            margin: 0 auto;
        }

        section h2 {
            color: #0d47a1;
            font-size: 2em;
            margin-bottom: 20px;
        }

        .contact-buttons a {
            display: inline-block;
            margin: 10px;
            padding: 12px 25px;
            background-color: #0d47a1;
            color: #ffffff;
            font-weight: bold;
            border-radius: 5px;
            transition: background-color 0.3s;
        }

        .contact-buttons a:hover {
            background-color: #1565c0;
        }

        footer {
            background-color: #1a237e;
            text-align: center;
            padding: 20px;
        }

        /* Sección de reseñas estilo tarjeta */
        .review {
            background-color: #0d47a1;
            padding: 20px;
            margin-bottom: 15px;
            border-radius: 5px;
        }

        /* Sección de Ubicación */
        iframe {
            width: 100%;
            height: 300px;
            border: 0;
            border-radius: 5px;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <header>
        <h1>Cerrajería Barbosa</h1>
    </header>

    <!-- Navegación -->
    <nav>
        <a href="#inicio">Inicio</a>
        <a href="#servicios">Servicios</a>
        <a href="#insumos">Insumos</a>
        <a href="#contactos">Contactos</a>
        <a href="#ubicacion">Ubicación</a>
        <a href="#resenas">Reseñas</a>
    </nav>

    <!-- Sección Inicio -->
    <section id="inicio">
        <h2>Bienvenido a Cerrajería Barbosa</h2>
        <p>Su cerrajería de confianza en Barbosa, Santander. Especialistas en llaves con chip, programación de alarmas y todo tipo de servicios de cerrajería.</p>
        <div class="contact-buttons">
            <a href="https://wa.me/573229495816" target="_blank">WhatsApp</a>
            <a href="tel:+573144816095">Llamar</a>
            <a href="https://www.facebook.com/share/19N7nGWdpJ/" target="_blank">Facebook</a>
        </div>
    </section>

    <!-- Sección Servicios -->
    <section id="servicios">
        <h2>Servicios</h2>
        <ul>
            <li>Programación de llaves con chip</li>
            <li>Duplicado y creación de llaves originales</li>
            <li>Programación de alarmas originales</li>
            <li>Servicios de cerrajería general</li>
        </ul>
    </section>

    <!-- Sección Insumos -->
    <section id="insumos">
        <h2>Insumos</h2>
        <p>Ofrecemos venta de insumos y repuestos para cerrajería y sistemas de seguridad. Llaves, chips, controles remotos y más.</p>
    </section>

    <!-- Sección Contactos -->
    <section id="contactos">
        <h2>Contactos</h2>
        <p>WhatsApp: <a href="https://wa.me/573229495816" target="_blank">3229495816</a></p>
        <p>Teléfono: <a href="tel:+573144816095">3144816095</a></p>
        <p>Facebook: <a href="https://www.facebook.com/share/19N7nGWdpJ/" target="_blank">Cerrajería Barbosa</a></p>
    </section>

    <!-- Sección Ubicación -->
    <section id="ubicacion">
        <h2>Ubicación</h2>
        <iframe 
            src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3976.123456789!2d-73.000000!3d6.500000!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8e4420abcdef1234%3A0xabcdef1234567890!2sBarbosa%2C%20Santander!5e0!3m2!1ses!2sco!4v1692835200000" 
            allowfullscreen="" loading="lazy">
        </iframe>
    </section>

    <!-- Sección Reseñas -->
    <section id="resenas">
        <h2>Reseñas</h2>
        <div class="review">
            <p>"Excelente servicio, programaron mi llave con chip en minutos!" - Cliente satisfecho</p>
        </div>
        <div class="review">
            <p>"Profesionales y rápidos, totalmente recomendados." - Cliente satisfecho</p>
        </div>
    </section>

    <!-- Footer -->
    <footer>
        <p>&copy; 2025 Cerrajería Barbosa | Todos los derechos reservados</p>
    </footer>

</body>
</html>


