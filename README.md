<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diamon Style</title>
    <style>
        /* Estilos generales */
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
            line-height: 1.6;
            text-align: center;
        }

        header {
            background-color: #111;
            padding: 20px;
        }

        header img {
            max-width: 100px;
            border-radius: 50%;
            margin-bottom: 10px;
        }

        header h1 {
            margin: 0;
            font-size: 2.5em;
            color: #d4af37; /* Dorado */
        }

        header p {
            margin: 5px 0 0;
            font-size: 1.2em;
            color: #ccc;
        }

        nav {
            background-color: #222;
            padding: 10px;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
        }

        nav ul li {
            margin: 0 15px;
        }

        nav ul li a {
            color: #d4af37;
            text-decoration: none;
            font-weight: bold;
        }

        nav ul li a:hover {
            color: #fff;
        }

        section {
            padding: 20px;
            margin: 20px auto;
            max-width: 800px;
            background-color: #111;
            border-radius: 10px;
        }

        section h2 {
            color: #d4af37;
            font-size: 2em;
            margin-bottom: 10px;
        }

        section p {
            color: #ccc;
        }

        section img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-top: 10px;
        }

        .productos {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 20px;
        }

        .producto {
            background-color: #222;
            padding: 15px;
            border-radius: 10px;
            width: 200px;
        }

        .producto img {
            max-width: 100%;
            border-radius: 10px;
        }

        .producto h3 {
            color: #d4af37;
            font-size: 1.2em;
            margin: 10px 0;
        }

        .producto p {
            color: #ccc;
        }

        form {
            max-width: 400px;
            margin: 0 auto;
            text-align: left;
        }

        form label {
            display: block;
            margin: 10px 0 5px;
            color: #d4af37;
        }

        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 10px;
            border: 1px solid #444;
            border-radius: 5px;
            background-color: #222;
            color: #fff;
        }

        form button {
            background-color: #d4af37;
            color: #000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        form button:hover {
            background-color: #b6952e;
        }

        footer {
            background-color: #111;
            padding: 10px;
            color: #ccc;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <img src="logo-diamon-style.jpg" alt="Logo Diamon Style">
        <h1>Diamon Style</h1>
        <p>Lujo y estilo en tenis y relojes.</p>
    </header>

    <nav>
        <ul>
            <li><a href="#inicio">Inicio</a></li>
            <li><a href="#relojes">Relojes</a></li>
            <li><a href="#tenis">Tenis</a></li>
            <li><a href="#contacto">Contacto</a></li>
        </ul>
    </nav>

    <section id="inicio">
        <h2>Bienvenido a Diamon Style</h2>
        <p>Descubre nuestra exclusiva colección de relojes y tenis de las mejores marcas.</p>
        <img src="diamon-style-inicio.jpg" alt="Diamon Style">
    </section>

    <section id="relojes">
        <h2>Relojes</h2>
        <div class="productos">
            <div class="producto">
                <img src="reloj-tecnomarine.jpg" alt="Tecnomarine">
                <h3>Tecnomarine</h3>
                <p>Relojes elegantes y modernos.</p>
            </div>
            <div class="producto">
                <img src="reloj-rolex.jpg" alt="Rolex">
                <h3>Rolex</h3>
                <p>Lujo y precisión en cada detalle.</p>
            </div>
            <div class="producto">
                <img src="reloj-cartier.jpg" alt="Cartier">
                <h3>Cartier</h3>
                <p>Diseños icónicos y sofisticados.</p>
            </div>
            <div class="producto">
                <img src="reloj-d-shock.jpg" alt="D-Shock">
                <h3>D-Shock</h3>
                <p>Resistencia y estilo deportivo.</p>
            </div>
            <div class="producto">
                <img src="reloj-casio.jpg" alt="Casio">
                <h3>Casio</h3>
                <p>Funcionalidad y diseño clásico.</p>
            </div>
            <div class="producto">
                <img src="reloj-invicta.jpg" alt="Invicta">
                <h3>Invicta</h3>
                <p>Audacia y originalidad.</p>
            </div>
        </div>
    </section>

    <section id="tenis">
        <h2>Tenis</h2>
        <div class="productos">
            <div class="producto">
                <img src="tenis-adidas.jpg" alt="Adidas">
                <h3>Adidas</h3>
                <p>Innovación y rendimiento.</p>
            </div>
            <div class="producto">
                <img src="tenis-new-balance.jpg" alt="New Balance">
                <h3>New Balance</h3>
                <p>Comodidad y estilo urbano.</p>
            </div>
            <div class="producto">
                <img src="tenis-nike.jpg" alt="Nike">
                <h3>Nike</h3>
                <p>Tecnología y diseño vanguardista.</p>
            </div>
            <div class="producto">
                <img src="tenis-puma.jpg" alt="Puma">
                <h3>Puma</h3>
                <p>Actitud y estilo deportivo.</p>
            </div>
            <div class="producto">
                <img src="tenis-balenciaga.jpg" alt="Balenciaga">
                <h3>Balenciaga</h3>
                <p>Lujo y moda en cada paso.</p>
            </div>
        </div>
    </section>

    <section id="contacto">
        <h2>Contacto</h2>
        <p>¿Tienes preguntas o deseas hacer un pedido especial? ¡Contáctanos!</p>
        <form action="https://formspree.io/f/{TU_ID_DE_FORMULARIO}" method="POST">
            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="mensaje">Mensaje:</label>
            <textarea id="mensaje" name="mensaje" rows="4" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Diamon Style. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
