<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Miguel | Virtual Assistant & Customer Support | Bilingual EN–ES</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #2c3e50;
            --accent-color: #3498db;
            --cta-color: #e67e22;
            --whatsapp-color: #25d366;
            --text-color: #333;
            --light-bg: #f4f7f6;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            margin: 0;
            padding: 0;
            background-color: white;
            scroll-behavior: smooth;
        }

        header {
            background: linear-gradient(135deg, var(--primary-color), var(--accent-color));
            color: white;
            padding: 100px 20px;
            text-align: center;
        }

        .container {
            max-width: 900px;
            margin: auto;
            padding: 20px;
        }

        h1 { margin-bottom: 10px; font-size: 2.5em; }
        h2 { color: var(--primary-color); border-bottom: 2px solid var(--accent-color); padding-bottom: 10px; margin-top: 40px; }

        .intro { font-size: 1.2em; margin-bottom: 40px; text-align: center; color: #555; }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin-top: 30px;
        }

        .card {
            background: var(--light-bg);
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        ul { list-style: none; padding: 0; }
        li { margin-bottom: 12px; display: flex; align-items: center; }
        li i { color: var(--accent-color); margin-right: 12px; }

        .about-section {
            margin-top: 60px;
            display: flex;
            align-items: center;
            gap: 40px;
            flex-wrap: wrap;
        }
        .profile-img {
            width: 220px;
            height: 220px;
            border-radius: 50%;
            border: 5px solid var(--accent-color);
            object-fit: cover;
            background-color: #eee;
        }

        .info-bar {
            background: #fdfdfd;
            border: 1px solid #eee;
            padding: 25px;
            border-radius: 12px;
            margin-top: 40px;
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .info-item { text-align: center; margin: 15px; }
        .info-item strong { display: block; color: var(--primary-color); }
        .info-item a { color: var(--text-color); text-decoration: none; font-weight: bold; }

        /* Botón WhatsApp Flotante */
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 40px;
            right: 40px;
            background-color: var(--whatsapp-color);
            color: #FFF;
            border-radius: 50px;
            text-align: center;
            font-size: 30px;
            box-shadow: 2px 2px 3px #999;
            z-index: 100;
            display: flex;
            align-items: center;
            justify-content: center;
            text-decoration: none;
            transition: 0.3s;
        }
        .whatsapp-float:hover { transform: scale(1.1); background-color: #128c7e; }

        /* Formulario */
        .contact-form {
            background: var(--primary-color);
            padding: 40px;
            border-radius: 12px;
            color: white;
            margin-top: 50px;
        }
        .form-group { margin-bottom: 15px; }
        input, textarea {
            width: 100%;
            padding: 12px;
            border-radius: 6px;
            border: none;
            margin-top: 5px;
            box-sizing: border-box;
            font-family: inherit;
        }

        .cta-button {
            display: inline-block;
            background: var(--cta-color);
            color: white;
            padding: 15px 40px;
            text-decoration: none;
            border-radius: 50px;
            font-weight: bold;
            transition: 0.3s;
            border: none;
            cursor: pointer;
            font-size: 1em;
        }
        .cta-button:hover { background: #d35400; transform: scale(1.03); }

        footer { text-align: center; padding: 60px 20px; color: #888; border-top: 1px solid #eee; }
    </style>
</head>
<body>

<a href="https://wa.me/34711087707" class="whatsapp-float" target="_blank">
    <i class="fab fa-whatsapp"></i>
</a>

<header>
    <div class="container">
        <h1>Virtual Assistant & Customer Support</h1>
        <p style="font-size: 1.3em;">Bilingual EN–ES | Reliable & Detail-Oriented</p>
        <a href="#contacto" class="cta-button">EMPECEMOS A TRABAJAR</a>
    </div>
</header>

<div class="container">
    <section>
        <p class="intro">
            Hola, soy <strong>Miguel</strong>. Ofrezco soporte bilingüe con experiencia en soporte al cliente y gestión administrativa. 
            Trabajo de forma <strong>estructurada, clara y orientada a soluciones</strong>.
        </p>
    </section>

    <div class="grid">
        <section class="card">
            <h2><i class="fas fa-tools"></i> ¿Cómo puedo ayudarte?</h2>
            <ul>
                <li><i class="fas fa-check"></i> Atención al cliente (Email/Chat)</li>
                <li><i class="fas fa-check"></i> Gestión de agendas y correos</li>
                <li><i class="fas fa-check"></i> Organización de documentos</li>
                <li><i class="fas fa-check"></i> Google Workspace, Notion, Trello</li>
            </ul>
        </section>

        <section class="card">
            <h2><i class="fas fa-star"></i> Valor añadido</h2>
            <ul>
                <li><i class="fas fa-check"></i> Comunicación clara y profesional</li>
                <li><i class="fas fa-check"></i> Capacidad técnica y humana</li>
                <li><i class="fas fa-check"></i> Fiabilidad y cumplimiento de plazos</li>
                <li><i class="fas fa-check"></i> Enfoque en startups y profesionales</li>
            </ul>
        </section>
    </div>

    <section id="about" class="about-section">
        <div style="flex: 1; min-width: 300px;">
            <h2>Sobre mí</h2>
            <p>Entiendo que delegar es confiar parte de tu visión a otra persona. Mi enfoque combina la eficiencia técnica con una comunicación empática para que sientas que tu negocio está en buenas manos.</p>
            <p>Soy una persona apasionada por el orden y la puntualidad, siempre buscando optimizar procesos para que tú puedas enfocarte en lo que realmente importa: hacer crecer tu proyecto.</p>
        </div>
        <div style="flex: 0 1 250px; text-align: center;">
            <img src="https://via.placeholder.com/220?text=Miguel" alt="Miguel - Virtual Assistant" class="profile-img">
        </div>
    </section>

    <div class="info-bar">
        <div class="info-item"><strong>Disponibilidad</strong> 3–4 horas/día</div>
        <div class="info-item"><strong>Zona Horaria</strong> Europa (CET)</div>
        <div class="info-item"><strong>WhatsApp</strong> <a href="https://wa.me/34711087707">+34 711 08 77 07</a></div>
        <div class="info-item"><strong>Idiomas</strong> ES (Nativo) · EN (Avanzado)</div>
    </div>

    <section id="contacto" class="contact-form">
        <h2 style="color: white; border-color: var(--cta-color); margin-top: 0;">Contacto</h2>
        <p>Envíame un mensaje y hablemos de cómo puedo facilitar tu día a día.</p>
        <form action="https://formspree.io/f/806324f1ac33494f81a3fbd301414305" method="POST">
            <div class="form-group">
                <label>Nombre</label>
                <input type="text" name="nombre" placeholder="Tu nombre" required>
            </div>
            <div class="form-group">
                <label>Email</label>
                <input type="email" name="email" placeholder="tu@email.com" required>
            </div>
            <div class="form-group">
                <label>Mensaje</label>
                <textarea name="mensaje" rows="4" placeholder="¿En qué puedo apoyarte?" required></textarea>
            </div>
            <button type="submit" class="cta-button">ENVIAR SOLICITUD</button>
        </form>
    </section>
</div>

<footer>
    <p>&copy; 2026 Miguel | Virtual Assistant & Customer Support.<br>
    Eficiencia bilingüe para tu negocio remoto.</p>
</footer>

</body>
</html>
