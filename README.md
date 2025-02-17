<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>D&F Precisión</title>
    <!-- Favicon -->
    <link rel="apple-touch-icon" sizes="57x57" href="/apple-icon-57x57.png">
    <link rel="apple-touch-icon" sizes="60x60" href="/apple-icon-60x60.png">
    <link rel="apple-touch-icon" sizes="72x72" href="/apple-icon-72x72.png">
    <link rel="apple-touch-icon" sizes="76x76" href="/apple-icon-76x76.png">
    <link rel="apple-touch-icon" sizes="114x114" href="/apple-icon-114x114.png">
    <link rel="apple-touch-icon" sizes="120x120" href="/apple-icon-120x120.png">
    <link rel="apple-touch-icon" sizes="144x144" href="/apple-icon-144x144.png">
    <link rel="apple-touch-icon" sizes="152x152" href="/apple-icon-152x152.png">
    <link rel="apple-touch-icon" sizes="180x180" href="/apple-icon-180x180.png">
    <link rel="icon" type="image/png" sizes="192x192" href="/android-icon-192x192.png">
    <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="96x96" href="/favicon-96x96.png">
    <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
    <link rel="manifest" href="/manifest.json">
    <meta name="msapplication-TileColor" content="#ffffff">
    <meta name="msapplication-TileImage" content="/ms-icon-144x144.png">
    <meta name="theme-color" content="#ffffff">
    <!-- Fuentes y estilos -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://images.unsplash.com/photo-1666634157070-6fd830fb5672?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D');
            background-size: cover;
            background-position: center;
            background-attachment: fixed;
            color: #333;
        }
        header {
            background-image: url('https://drive.google.com/uc?export=view&id=1TH70Y8t1fN8W5j2PC2eG-cLl2XGOruDx');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 150px 20px;
            text-align: center;
        }
        header h1 {
            font-size: 80px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            background-color: rgba(0, 0, 0, 0.86);
            display: inline-block;
            padding: 30px 45px;
            border-radius: 10px;
        }
        header p {
            font-size: 32px;
            margin-top: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            background-color: rgba(0, 0, 0, 0.86);
            display: inline-block;
            padding: 15px 25px;
            border-radius: 5px;
        }
        section {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            padding: 20px;
            max-width: 1000px;
            animation: fadeIn 0.5s ease-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .gallery img {
            width: 100%;
            max-width: 300px;
            margin: 10px;
            border: 2px solid #ddd;
            border-radius: 5px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .gallery img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        form {
            max-width: 400px;
            margin: auto;
            display: flex;
            flex-direction: column;
        }
        input, textarea, button {
            margin: 5px 0;
            padding: 10px;
            font-size: 16px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }
        button {
            background-color: #28a745;
            color: white;
            border: none;
            cursor: pointer;
            transition: background-color 0.3s ease;
        }
        button:hover {
            background-color: #218838;
        }
        .justificado {
            text-align: center;
            max-width: 800px;
            margin: auto;
            font-size: 18px;
            line-height: 1.6;
        }
        .mision-vision {
            display: flex;
            justify-content: center;
            gap: 20px;
            max-width: 900px;
            margin: auto;
        }
        @media (max-width: 600px) {
            .mision-vision {
                flex-direction: column;
            }
            .mision-vision div {
                width: 100%;
            }
            header h1 {
                font-size: 48px;
                padding: 15px 30px;
            }
            header p {
                font-size: 18px;
                padding: 8px 16px;
            }
        }
        footer {
            background-color: rgba(51, 51, 51, 0.9);
            color: white;
            padding: 20px;
            text-align: center;
        }
        footer a {
            color: #28a745;
            margin: 0 10px;
            text-decoration: none;
        }
        .servicios-container {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            padding: 20px;
        }
        .servicio {
            text-align: center;
            background-color: rgba(255, 255, 255, 0.95);
            border-radius: 10px;
            padding: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .servicio:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        }
        .servicio img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        .servicio p {
            font-size: 16px;
            color: #555;
        }
        .horarios {
            text-align: center;
            margin: 20px 0;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .horarios h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .horarios p {
            font-size: 16px;
            color: #555;
        }
        .ubicacion {
            text-align: center;
            margin: 20px 0;
            padding: 20px;
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .ubicacion h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .ubicacion iframe {
            width: 100%;
            height: 300px;
            border: 0;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <h1>D&F Precisión</h1>
        <p>"Precisión en cada pieza, calidad en cada proyecto"</p>
    </header>
    <main>
        <section>
            <h2 style="text-align: center; font-size: 32px;">Sobre Nosotros</h2>
            <p class="justificado">
                En D&F Precisión, nos especializamos en el diseño y fabricación de piezas mecánicas de alta precisión. 
                Brindamos servicios de mecanizado, prototipado y producción en serie, asegurando calidad en cada detalle. 
                Nuestro equipo combina experiencia y tecnología para transformar tus ideas en productos funcionales con acabados impecables.
            </p>
        </section>
        <section>
            <h2 style="text-align: center; font-size: 32px;">Servicios</h2>
            <div class="servicios-container">
                <div class="servicio">
                    <img src="https://images.unsplash.com/photo-1652888510609-ed2d2ad64d6b?q=80&w=1527&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Torneado">
                    <p>Torneado y fresado de precisión</p>
                </div>
                <div class="servicio">
                    <img src="https://d2t1xqejof9utc.cloudfront.net/screenshots/pics/ee5506e1dc1d30cf73826786234ade75/large.jpg" alt="Diseño">
                    <p>Diseño y fabricación de piezas mecánicas</p>
                </div>
                <div class="servicio">
                    <img src="https://images.unsplash.com/photo-1729854808531-b3cf8c341993?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Prototipado">
                    <p>Prototipado y producción en serie</p>
                </div>
                <div class="servicio">
                    <img src="https://images.unsplash.com/photo-1736161999630-9feb825596a6?q=80&w=1470&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Ingeniería">
                    <p>Ingeniería inversa y optimización de componentes</p>
                </div>
                <div class="servicio">
                    <img src="https://images.unsplash.com/photo-1738162837451-2041c1418f54?q=80&w=1632&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Corte láser y grabado">
                    <p>Corte láser y grabado</p>
                </div>
            </div>
            <a href="#cotizacion" style="text-decoration: none;">
                <button style="margin-top: 20px; display: block; margin-left: auto; margin-right: auto;">Solicitar Cotización</button>
            </a>
        </section>
        <section class="mision-vision">
            <div>
                <h2>Misión</h2>
                <p>En D&F Precisión, nos dedicamos a transformar la industria del mecanizado a través de un servicio de excelencia. 
                   Nuestra misión es ofrecer soluciones innovadoras en diseño y fabricación, con un alto nivel de precisión y eficiencia. 
                   Nos diferenciamos por nuestro nivel de respuesta, compromiso con la calidad y enfoque en la optimización de procesos para nuestros clientes, 
                   contribuyendo así a su competitividad en el mercado.</p>
            </div>
            <div>
                <h2>Visión</h2>
                <p>Ser líderes en la industria del mecanizado, reconocidos por nuestro nivel de servicio, precisión y capacidad de innovación. 
                   Buscamos posicionarnos como la mejor opción para empresas que requieren soluciones eficientes y de alta calidad, 
                   destacándonos en un mercado cada vez más competitivo.</p>
            </div>
        </section>
        <section>
        <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Diseño y Fabricación</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        .gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            gap: 10px;
            padding: 20px;
        }
        .gallery img {
            width: 300px;
            height: auto;
            border-radius: 10px;
            box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.1);
        }
    </style>
<html lang="es">
<body>
    <h1>Diseño y Fabricación</h1>
    <h2>Galería</h2>
    <div class="gallery">
        <img src="https://img.freepik.com/foto-gratis/maquina-metalica-fabrica_1112-248.jpg?t=st=1738622894~exp=1738626494~hmac=a3eda834cc7c5e97139988ced8a6556e32d583926fa74303113e28e6d674d78c&w=740" alt="Máquina metálica en fábrica">
        <img src="https://img.freepik.com/foto-gratis/cortar-madera-contrachapada_1098-13347.jpg?t=st=1738625189~exp=1738628789~hmac=4c4456da7bb770b6a7e847b9155de4d7e2b8a12164f2f3a3539a2c112886c11d&w=740">
        <img src="https://img.freepik.com/foto-gratis/taladro-metal-industrial-taller-metalurgico_342744-520.jpg?t=st=1738622907~exp=1738626507~hmac=75ad33ac7867ef6c1acd84594a595c5250874d7ed121d99fc4daa7c3b8cadfce&w=740" alt="Taladro en taller metalúrgico">
        <img src="https://images.unsplash.com/photo-1727292486169-33eba0865c99?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Maquinaria industrial">
        <img src="https://images.unsplash.com/photo-1727292485794-925866ec2372?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Piezas metálicas">
        <img src="https://images.unsplash.com/photo-1602223114290-ba6de2938acc?q=80&w=1374&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="Torno industrial">
     </div>
        <section id="cotizacion">
            <h2>Solicita una Cotización</h2>
            <form action="https://formspree.io/f/myyabcde" method="POST">
                <input type="text" name="nombre" placeholder="Nombre" required>
                <input type="email" name="correo" placeholder="Correo" required>
                <textarea name="mensaje" placeholder="Descripción del trabajo" required></textarea>
                <button type="submit">Enviar</button>
            </form>
        </section>
        <!-- Sección de Horarios de Atención -->
        <section class="horarios">
            <h2>Horarios de Atención</h2>
            <p>Lunes a Viernes: 9:00 a 18:00</p>
            <p>Sábados: 9:00 a 12:00</p>
            <p>Para atención fuera de horario, contáctanos por correo o WhatsApp.</p>
        </section>
        <!-- Sección de Ubicación -->
        <section class="ubicacion">
            <h2>Ubicación</h2>
            <p>Col. José Clemente Orozco, Guadalajara, Jalisco.</p>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3733.383684798084!2d-103.37126668459115!3d20.653557486202835!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8428b1f8a5f5f5f5%3A0x5f5f5f5f5f5f5f5f!2sCol.%20Jos%C3%A9%20Clemente%20Orozco%2C%20Guadalajara%2C%20Jal.!5e0!3m2!1ses!2smx!4v1633036800000!5m2!1ses!2smx" 
                    allowfullscreen="" 
                    loading="lazy">
            </iframe>
         </section>
        <section>
            <h2>Contacto</h2>
            <p>Para más información, no dudes en contactarnos:</p>
            <ul style="list-style-type: none; padding-left: 0;">
                <li><strong>Joshua Solis:</strong> 
                    <a href="tel:3315841619">331 584 1619</a> | 
                    <a href="mailto:Joshuasolis_05@hotmail.com">Joshuasolis_05@hotmail.com</a>
                </li>
                <li><strong>Francisco Antonio:</strong> 
                    <a href="tel:3310000793">331 000 0793</a> | 
                    <a href="mailto:Fsolyluna@hotmail.com">Fsolyluna@hotmail.com</a>
                </li>
            </ul>
        </section>
    </main>
    <footer>
        <p>Contacto: Fsolyluna@hotmail.com | Tel: +52 331 000 0793</p>
        <p>Síguenos en:
            <a href="#">Facebook</a>
            <a href="#">Instagram</a>
            <a href="#">LinkedIn</a>
        </p>
    </footer>
    <a href="https://wa.me/523310000793" target="_blank" style="position: fixed; bottom: 20px; right: 20px; background-color: #25D366; color: white; padding: 15px; border-radius: 50%; text-decoration: none; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);">
        <i class="fab fa-whatsapp" style="font-size: 24px;"></i>
    </a>
</body>
</html>

