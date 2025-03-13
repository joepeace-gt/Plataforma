<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Wireframe Plataforma Migratoria</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=SF+Pro+Display:wght@300;400;600;800&display=swap');
        
        body {
            font-family: 'SF Pro Display', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom, #f5f5f7, #e5e5e7);
            color: #1d1d1f;
        }
        .navbar {
            background-color: rgba(255, 255, 255, 0.95);
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.05);
            position: fixed;
            width: 100%;
            top: 0;
            backdrop-filter: blur(10px);
            font-size: 18px;
            z-index: 1000;
        }
        .hero {
            text-align: center;
            padding: 100px 20px;
            background: url('https://source.unsplash.com/1600x900/?migration,world') no-repeat center center/cover;
            color: white;
            font-size: 50px;
            font-weight: 800;
        }
        .container {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 50px;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
        }
        .card {
            width: 80%;
            background: white;
            padding: 50px;
            margin: 20px;
            border-radius: 30px;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.1);
            text-align: center;
            transition: transform 0.3s ease-in-out, box-shadow 0.3s ease-in-out;
            font-size: 22px;
        }
        .card:hover {
            transform: scale(1.03);
            box-shadow: 0 20px 45px rgba(0, 0, 0, 0.15);
        }
        .footer {
            background-color: #e5e5e7;
            padding: 40px;
            text-align: center;
            margin-top: 50px;
            font-size: 18px;
            color: #6e6e73;
        }
        .highlight {
            font-weight: bold;
            color: #0071e3;
            font-size: 1.8em;
        }
        ul {
            list-style-type: none;
            padding: 0;
            font-size: 20px;
        }
        ul li {
            padding: 10px 0;
        }
        button {
            background-color: #0071e3;
            color: white;
            border: none;
            padding: 16px 40px;
            border-radius: 25px;
            font-size: 20px;
            cursor: pointer;
            transition: background-color 0.3s ease-in-out, transform 0.2s ease-in-out;
        }
        button:hover {
            background-color: #005bb5;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <div class="navbar">
        <div class="highlight">Centro de Información Migratoria</div>
        <div>Menú | Servicios | Contacto</div>
    </div>
    <div class="hero">
        Tu destino, tu futuro.
    </div>
    <div class="container">
        <div class="card">🔍 <span class="highlight">Buscador de Trámites Migratorios</span><br><br><button>Buscar</button></div>
        <div class="card">📋 <span class="highlight">Categorías:</span>
            <ul>
                <li>Servicios Migratorios y Consulares</li>
                <li>Apoyo y Protección a Migrantes</li>
                <li>Formación y Empleo</li>
                <li>Salud y Bienestar</li>
                <li>Trámites y Pagos</li>
                <li>Investigaciones y Datos</li>
                <li>Denuncias y Emergencias</li>
            </ul>
        </div>
        <div class="card">📞 <span class="highlight">Chat de Asistencia</span> | 🤖 Chatbot con IA</div>
        <div class="card">🔔 <span class="highlight">Noticias y Actualizaciones Migratorias</span></div>
        <div class="card">💳 <span class="highlight">Pagos y Trámites Electrónicos</span> (Pasaportes, Apostillas, Visas)</div>
        <div class="card">📚 <span class="highlight">Repositorio de Estudios e Investigaciones</span></div>
        <div class="card">📄 <span class="highlight">Portal de Transparencia</span> (Presupuestos, Normativas, Planes de Trabajo)</div>
        <div class="card">📝 <span class="highlight">Formulario de Trámites</span> (Solicitud de Asilo, Renovación de Pasaporte)</div>
        <div class="card">🔐 <span class="highlight">Iniciar Sesión | Registrarse</span> (OAuth, Google, Facebook)<br><br><button>Ingresar</button></div>
    </div>
    <div class="footer">&copy; 2025 Centro de Información Migratoria - Seguridad y Transparencia</div>
</body>
</html>
