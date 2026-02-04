<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>AUTOLAVADO</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            background-color: #F2F2F2;
            font-family: Arial, sans-serif;
            color: #2C2C2C;
            margin: 20px;
        }

        h1 {
            color: #0B3C5D;
            text-align: center;
        }

        h2 {
            color: #1CA7EC;
            margin-top: 30px;
        }

        p {
            background-color: #FFFFFF;
            padding: 12px;
            border-radius: 8px;
        }

        ul {
            background-color: #FFFFFF;
            padding: 15px;
            border-radius: 8px;
            list-style: none;
        }

        li {
            margin-bottom: 8px;
        }

        img {
            display: block;
            margin: 15px auto;
            border-radius: 10px;
            max-width: 100%;
        }

        .precio {
            color: #E67E22;
            font-weight: bold;
        }

        /* BOTONES */
        .botones {
            text-align: center;
            margin: 25px 0;
        }

        .boton {
            background-color: #1CA7EC;
            color: white;
            padding: 12px 18px;
            margin: 6px;
            border-radius: 8px;
            text-decoration: none;
            display: inline-block;
            font-size: 15px;
            transition: transform 0.2s, background-color 0.2s;
        }

        .boton:hover {
            background-color: #0B3C5D;
            transform: scale(1.05);
        }

        /* TARJETAS */
        .cards {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 15px;
        }

        .card {
            background-color: #FFFFFF;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1);
            transition: transform 0.2s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        footer {
            margin-top: 40px;
            text-align: center;
            background-color: #0B3C5D;
            color: white;
            padding: 15px;
            border-radius: 10px;
            font-weight: bold;
        }

        /* RESPONSIVE MAPA */
        iframe {
            max-width: 100%;
        }
    </style>
</head>

<body>

<h1>🚗 AUTOLAVADO</h1>

<div class="botones">
    <a href="#precios" class="boton">💲 Ver precios</a>
    <a href="tel:4651233567" class="boton">📞 Llamar</a>
    <a href="https://wa.me/524651233567?text=Hola%20quiero%20información%20sobre%20un%20lavado" class="boton">💬 WhatsApp</a>
</div>

<h2>BIENVENIDOS</h2>
<p>
Cuidamos tu auto como si fuera nuestro.  
Lavado rápido, seguro y con productos de calidad.
</p>

<img src="LIMPIEZA.jpg" width="350">

<h2>¿Quiénes somos?</h2>
<p>
Somos un autolavado comprometido con el cuidado de tu vehículo, ofreciendo un servicio confiable y de calidad.
</p>

<img src="AUTOLAVADO.jpg" width="350">

<h2>SERVICIOS</h2>
<div class="cards">
    <div class="card">🚿 Lavado exterior</div>
    <div class="card">🧹 Lavado interior</div>
</div>

<img src="SERVICIOS.jpg" width="350">

<h2>HORARIOS</h2>
<ul>
    <li>⏰ Lunes, miércoles y viernes: 2:00 pm – 6:00 pm</li>
    <li>⏰ Martes y jueves: 1:40 pm – 6:00 pm</li>
    <li>⏰ Sábado: 11:30 am – 4:00 pm</li>
</ul>

<h2 id="precios">PRECIOS</h2>
<div class="cards">
    <div class="card">Lavado exterior<br><span class="precio">$80 MXN</span></div>
    <div class="card">Lavado interior<br><span class="precio">$100 MXN</span></div>
    <div class="card">Lavado completo<br><span class="precio">$150 MXN</span></div>
    <div class="card">Encerado<br><span class="precio">$200 MXN</span></div>
</div>

<img src="AUTO LAVADO.jpg" width="350">

<h2>UBICACIÓN</h2>
<p>
📍 Clavellinas, Asientos, Aguascalientes.
</p>

<!-- MAPA NO TOCADO -->
<div style="text-align:center;">
<iframe
        src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d2197.460163724839!2d-102.13685286935733!3d22.13844963623206!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1sen!2smx!4v1770213900060!5m2!1sen!2smx"
        width="600"
        height="450"
        style="border:0;"
        allowfullscreen=""
        loading="lazy"
        referrerpolicy="no-referrer-when-downgrade">
</iframe>
</div>

<h2>CONTÁCTANOS</h2>
<ul>
    <li>📞 465 123 3567</li>
    <li>📧 Autolavado1207@gmail.com</li>
</ul>

<div class="botones">
    <a href="#" class="boton">📘 Facebook</a>
    <a href="#" class="boton">📸 Instagram</a>
    <a href="#" class="boton">🎵 TikTok</a>
</div>

<footer>
    JEISON JESUS GARCIA CALDERA
</footer>

</body>
</html>
