<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Viral Pro - Innovación y Juegos Futuristas</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@picocss/pico@1/css/pico.min.css">
    <style>
        body {
            margin: 0;
            font-family: 'Arial', sans-serif;
            background: #121212;
            color: #e0e0e0;
            overflow-x: hidden;
        }
        header {
            background: #1e1e1e;
            padding: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            z-index: 1000;
            box-shadow: 0 4px 8px rgba(0,0,0,0.8);
        }
        header h1 {
            margin: 0;
            color: #00ff00;
            font-size: 2.5em;
            text-shadow: 0 0 10px rgba(0,255,0,0.8);
        }
        .hero {
            height: 100vh;
            background: linear-gradient(to bottom, rgba(0,0,0,0.8), rgba(0,0,0,0.5)), #333;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
        }
        .hero h2 {
            color: #00ff00;
            font-size: 3em;
            margin: 0;
            text-shadow: 0 0 10px rgba(0,255,0,0.8);
        }
        .hero p {
            color: #d0d0d0;
            font-size: 1.5em;
        }
        .section {
            padding: 50px 20px;
            margin: 20px auto;
            max-width: 1200px;
            background: #1e1e1e;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0,0,0,0.5);
        }
        .section h2 {
            color: #00ff00;
        }
        .section p {
            color: #d0d0d0;
            line-height: 1.6;
        }
        .card {
            background: #2a2a2a;
            border-radius: 10px;
            padding: 20px;
            margin: 20px 0;
            box-shadow: 0 4px 8px rgba(0,0,0,0.5);
            border-left: 5px solid #00ff00;
        }
        .card h3 {
            color: #00ff00;
        }
        .card p {
            color: #d0d0d0;
        }
        .btn {
            display: inline-block;
            padding: 10px 20px;
            margin: 10px 0;
            background: #00ff00;
            color: #121212;
            text-decoration: none;
            border-radius: 5px;
            font-size: 1.2em;
            transition: background 0.3s, transform 0.3s;
        }
        .btn:hover {
            background: #00cc00;
            transform: scale(1.05);
        }
        footer {
            background: #1e1e1e;
            padding: 20px;
            color: #00ff00;
            text-align: center;
            width: 100%;
            box-shadow: 0 -4px 8px rgba(0,0,0,0.8);
        }
        .form-group {
            margin: 20px 0;
        }
        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: #00ff00;
        }
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 10px;
            border: 1px solid #00ff00;
            border-radius: 5px;
            background: #2a2a2a;
            color: #e0e0e0;
        }
        .form-group input[type="submit"] {
            background: #00ff00;
            color: #121212;
            cursor: pointer;
            border: none;
        }
        .form-group input[type="submit"]:hover {
            background: #00cc00;
        }
        .social-media {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .social-media a {
            color: #00ff00;
            font-size: 2em;
            transition: color 0.3s;
        }
        .social-media a:hover {
            color: #ffcc00;
        }
        .faq {
            margin-top: 30px;
        }
        .faq-item {
            margin-bottom: 20px;
        }
        .faq-question {
            font-weight: bold;
            color: #00ff00;
            cursor: pointer;
        }
        .faq-answer {
            display: none;
            margin-top: 10px;
            color: #d0d0d0;
        }
        #progress-bar {
            position: fixed;
            top: 0;
            left: 0;
            height: 5px;
            background: #00ff00;
            z-index: 9999;
        }
        .feature-list {
            list-style-type: none;
            padding: 0;
        }
        .feature-list li {
            margin-bottom: 10px;
            padding-left: 20px;
            position: relative;
        }
        .feature-list li::before {
            content: '➤';
            position: absolute;
            left: 0;
            color: #00ff00;
        }
        .color-cyan {
            color: #00ffff;
        }
        .color-magenta {
            color: #ff00ff;
        }
        .color-yellow {
            color: #ffff00;
        }
        .contact-info {
            display: flex;
            flex-direction: column;
            align-items: center;
        }
        .contact-info a {
            color: #00ff00;
            font-size: 1.5em;
            text-decoration: none;
            margin-top: 10px;
        }
        .contact-info a:hover {
            color: #ffcc00;
        }
    </style>
</head>
<body>
    <div id="progress-bar"></div>

    <header>
        <h1>Viral Pro</h1>
    </header>

    <div id="hero" class="hero">
        <h2>Bienvenido al Futuro del Gaming</h2>
        <p>Descubre nuestros juegos innovadores y experiencias tecnológicas únicas.</p>
        <a href="#games" class="btn">Explorar Juegos</a>
    </div>

    <main class="container">
        <div id="about" class="section">
            <h2>Sobre Nosotros</h2>
            <p>Viral Pro es una empresa joven y dinámica dedicada a crear experiencias de juego futuristas y soluciones tecnológicas innovadoras. Fundada en 2024, nuestra pasión es combinar la tecnología de vanguardia con la creatividad para ofrecer productos únicos que desafían los límites de lo posible.</p>
            <p>Nuestro equipo está compuesto por visionarios tecnológicos, diseñadores de juegos premiados y expertos en programación, todos unidos por el objetivo común de revolucionar la industria del gaming y la tecnología interactiva.</p>
            <div class="social-media">
                <a href="https://www.instagram.com/httpsjuegosdam.github.iojuegos?igsh=bjVieGwzOGdyaTdz" target="_blank"></a>
                <a href="https://twitter.com/damian_tech" target="_blank"></a>
                <a href="https://facebook.com/damiantechgames" target="_blank"></a>
            </div>
        </div>

        <div id="games" class="section">
            <h2>Nuestros Juegos</h2>
            <div class="card">
                <h3 class="color-cyan">Cyber Odyssey</h3>
                <p>Un juego de rol futurista con gráficos de última generación y una historia inmersiva. Sumérgete en un mundo donde la realidad y lo virtual se fusionan, desafiando tu percepción y habilidades estratégicas.</p>
                <ul class="feature-list">
                    <li>Mundo abierto con múltiples finales</li>
                    <li>Sistema de combate revolucionario basado en IA</li>
                    <li>Personalización profunda de personajes</li>
                    <li>Misiones generadas proceduralmente</li>
                </ul>
            </div>
            <div class="card">
                <h3 class="color-magenta">NeuroRacer</h3>
                <p>Experimenta carreras de alta velocidad en un mundo virtual controlado por tu mente. NeuroRacer utiliza tecnología de interfaz cerebro-computadora para ofrecer una experiencia de juego única y personalizada.</p>
                <ul class="feature-list">
                    <li>Control mental de vehículos</li>
                    <li>Pistas que cambian según tus emociones</li>
                    <li>Modo multijugador telepático</li>
                    <li>Entrenamiento cognitivo integrado</li>
                </ul>
            </div>
            <div class="card">
                <h3 class="color-yellow">EcoSim 2030</h3>
                <p>Simula y gestiona ecosistemas futuros en este juego educativo y desafiante. Aprende sobre sostenibilidad y toma decisiones críticas que afectarán el futuro del planeta en este innovador juego de simulación.</p>
                <ul class="feature-list">
                    <li>Simulación ecológica avanzada</li>
                    <li>Escenarios basados en datos científicos reales</li>
                    <li>Colaboración global en tiempo real</li>
                    <li>Impacto educativo medible</li>
                </ul>
            </div>
        </div>

        <div id="technology" class="section">
            <h2>Nuestra Tecnología</h2>
            <p>En Viral Pro, estamos a la vanguardia de la innovación tecnológica en la industria del gaming. Nuestras principales áreas de enfoque incluyen:</p>
            <div class="card">
                <h3 class="color-cyan">Inteligencia Artificial Avanzada</h3>
                <p>Utilizamos algoritmos de IA de última generación para crear NPCs más realistas, mundos de juego dinámicos y experiencias de juego adaptativas que evolucionan con cada jugador.</p>
            </div>
            <div class="card">
                <h3 class="color-magenta">Realidad Virtual y Aumentada</h3>
                <p>Nuestros juegos aprovechan lo último en tecnología VR y AR para ofrecer experiencias inmersivas que difuminan la línea entre el mundo real y el virtual.</p>
            </div>
            <div class="card">
                <h3 class="color-yellow">Tecnología Háptica Avanzada</h3>
                <p>Desarrollamos interfaces hápticas innovadoras que permiten a los jugadores sentir y interactuar con el mundo del juego de maneras nunca antes posibles.</p>
            </div>
        </div>

        <div id="future" class="section">
            <h2>Nuestra Visión de Futuro</h2>
            <p>En Viral Pro, no solo creamos juegos; estamos dando forma al futuro del entretenimiento interactivo. Nuestra visión incluye:</p>
            <ul class="feature-list">
                <li>Desarrollar experiencias de juego completamente inmersivas que involucren todos los sentidos.</li>
                <li>Crear mundos virtuales persistentes que evolucionen en tiempo real basados en las acciones colectivas de los jugadores.</li>
                <li>Utilizar el gaming como una herramienta para el aprendizaje acelerado y el desarrollo de habilidades en el mundo real.</li>
                <li>Fomentar conexiones sociales significativas a través de experiencias de juego compartidas y colaborativas.</li>
                <li>Impulsar avances en tecnología de interfaz cerebro-computadora para crear experiencias de juego controladas directamente por el pensamiento.</li>
            </ul>
        </div>

        <div id="community" class="section">
            <h2>Nuestra Comunidad</h2>
            <p>En Viral Pro, creemos que nuestra comunidad es el corazón de todo lo que hacemos. Nos esforzamos por crear un espacio inclusivo y colaborativo donde los jugadores puedan conectarse, compartir y crecer juntos.</p>
            <div class="card">
                <h3 class="color-cyan">Foros y Discusiones</h3>
                <p>Nuestros foros activos son un lugar donde los jugadores pueden compartir estrategias, discutir teorías y conectarse con otros fanáticos de nuestros juegos.</p>
            </div>
            <div class="card">
                <h3 class="color-magenta">Eventos de la Comunidad</h3>
                <p>Organizamos regularmente torneos en línea, sesiones de preguntas y respuestas con desarrolladores, y eventos especiales para mantener a nuestra comunidad comprometida y emocionada.</p>
            </div>
            <div class="card">
                <h3 class="color-yellow">Programa de Embajadores</h3>
                <p>Nuestro programa de embajadores permite a los jugadores más dedicados tener un impacto directo en el desarrollo de nuestros juegos y la dirección de nuestra comunidad.</p>
            </div>
        </div>
        
        <div id="faq" class="section faq">
            <h2>FAQ</h2>
            <div class="faq-item">
                <div class="faq-question">¿Qué es Viral Pro?</div>
                <div class="faq-answer">Viral Pro es una empresa dedicada a crear experiencias de juego futuristas y soluciones tecnológicas innovadoras.</div>
            </div>
            <div class="faq-item">
                <div class="faq-question">¿Cómo puedo unirme a la comunidad?</div>
                <div class="faq-answer">Puedes unirte a nuestra comunidad participando en nuestros foros y eventos, y siguiendo nuestras redes sociales.</div>
            </div>
            <div class="faq-item">
                <div class="faq-question">¿Dónde puedo encontrar más información sobre vuestros juegos?</div>
                <div class="faq-answer">Puedes encontrar más información sobre nuestros juegos en la sección de Juegos de esta página web.</div>
            </div>
        </div>
        
        <div id="contact" class="section">
            <h2>Contacto</h2>
            <p>Para cualquier consulta, puedes escribirnos directamente en Instagram:</p>
            <div class="contact-info">
                <a href"https://www.instagram.com/httpsjuegosdam.github.iojuegos?igsh=bjVieGwzOGdyaTdz" target="_blank"></a>
            </div>
        </div>
    </main>

    <footer class="container">
        <small>
            <a href="#about">Sobre Nosotros</a> • 
            <a href="#contact">Contacto</a>
        </small>
    </footer>
</body>
</html>



<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vi.pro
    </title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <div class="container">
            <hi vi. pro
            
        </h1>
            <nav>
                <ul>
                    <li><a href="#features">Características</a></li>
                    <li><a href="#pricing">Precios</a></li>
                    <li><a href="#testimonials">Testimonios</a></li>
                    <li><a href="#contact">Contacto</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="hero">
        <div class="container">
            <h2>Protección Total para tu Equipo</h2>
            <p>El mejor antivirus para mantener tu información segura y tu equipo libre de amenazas.</p>
            <a href="#features" class="btn">Descubre más</a>
        </div>
    </section>

    <section id="features" class="section">
        <div class="container">
            <h2>Características</h2>
            <div class="features-grid">
                <div class="feature">
                    <h3>Seguridad en Tiempo Real</h3>
                    <p>Protección constante contra virus y malware con actualizaciones automáticas.</p>
                </div>
                <div class="feature">
                    <h3>Escaneo Rápido</h3>
                    <p>Análisis veloz y eficiente para mantener tu equipo limpio y optimizado.</p>
                </div>
                <div class="feature">
                    <h3>Interfaz Intuitiva</h3>
                    <p>Fácil de usar para que cualquier persona pueda mantener su equipo seguro.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="pricing" class="section">
        <div class="container">
            <h2>Precios</h2>
            <div class="pricing-grid">
                <div class="price-option">
                    <h3>Básico</h3>
                    <p>$9.00 / año</p>
                    <ul>
                        <li>Protección en tiempo real</li>
                        <li>Escaneo rápido</li>
                        <li>Soporte básico</li>
                    </ul>
                    <a href="#" class="btn">Comprar</a>
                </div>
                <div class="price-option">
                    <h3>Premium</h3>
                    <p>$9.99 / año</p>
                    <ul>
                        <li>Todo en Básico</li>
                        <li>Protección avanzada</li>
                        <li>Soporte 24/7</li>
                    </ul>
                    <a href="#" class="btn">Comprar</a>
                </div>
            </div>
        </div>
    </section>

    <section id="testimonials" class="section">
        <div class="container">
            <h2>Testimonios</h2>
            <div class="testimonials-grid">
                <div class="testimonial">
                    <p>"El mejor antivirus que he usado. Mantiene mi equipo seguro y no lo ralentiza."</p>
                    <h4>Juan Pérez</h4>
                </div>
                <div class="testimonial">
                    <p>"Fácil de usar y muy efectivo. Lo recomiendo a todos."</p>
                    <h4>María López</h4>
                </div>
            </div>
        </div>
    </section>

    <footer id="contact" class="section">
        <div class="container">
            <h2>Contacto</h2>
            <p>Si tienes alguna pregunta, no dudes en <a href="mailto:info@antivirusultraseguro.com">contactarnos</a>.</p>
        </div>
    </footer>
</body>
</html>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    line-height: 1.6;
    color: #333;
}

.container {
    width: 80%;
    margin: auto;
    overflow: hidden;
}

header {
    background: #333;
    color: #fff;
    padding: 1rem 0;
}

header h1 {
    float: left;
}

header nav {
    float: right;
}

header nav ul {
    list-style: none;
}

header nav ul li {
    display: inline;
    margin-left: 20px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

#hero {
    background: #f4f4f4;
    padding: 2rem 0;
    text-align: center;
}

#hero h2 {
    margin-bottom: 1rem;
}

#hero .btn {
    background: #333;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
}

.section {
    padding: 2rem 0;
}

.features-grid, .pricing-grid, .testimonials-grid {
    display: flex;
    gap: 20px;
    justify-content: space-around;
}

.feature, .price-option, .testimonial {
    background: #f4f4f4;
    padding: 1rem;
    border-radius: 5px;
    text-align: center;
}

.price-option ul {
    list-style: none;
    margin: 1rem 0;
}

.price-option .btn {
    background: #333;
    color: #fff;
    padding: 0.5rem 1rem;
    text-decoration: none;
    border-radius: 5px;
}

footer {
    background: #333;
    color: #fff;
    text-align: center;
    padding: 1rem 0;
}

footer a {
    color: #fff;
    text-decoration: none;
}

