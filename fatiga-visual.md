<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Fatiga Visual - Prevención de Riesgos</title>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        :root {
            --primary-blue: #0f172a;
            --accent-blue: #3b82f6;
            --light-blue: #60a5fa;
            --badge-riesgo: #3b82f6; /* Color azul para Riesgo */
            --badge-medida: #0ea5e9; /* Nuevo color azul más claro para Medida */
            --card-bg: rgba(255, 255, 255, 0.05);
            --text-color: #f8fafc;
        }

        body {
            margin: 0;
            font-family: 'Segoe UI', sans-serif;
            background-color: var(--primary-blue);
            background-image: radial-gradient(circle at top right, #1e293b, #0f172a);
            color: var(--text-color);
            display: flex;
            min-height: 100vh;
        }

        /* Sidebar Lateral (Default) */
        nav {
            width: 260px;
            background: rgba(0, 0, 0, 0.3);
            border-right: 1px solid rgba(255, 255, 255, 0.1);
            padding: 2rem 1rem;
            backdrop-filter: blur(10px);
            position: fixed;
            height: 100vh;
            display: flex;
            flex-direction: column;
            box-sizing: border-box;
            z-index: 100;
        }

        nav h1 {
            font-size: 1.1rem;
            color: var(--light-blue);
            text-transform: uppercase;
            border-bottom: 2px solid var(--accent-blue);
            padding-bottom: 10px;
            margin-bottom: 2rem;
        }

        nav ul { list-style: none; padding: 0; margin: 0; flex-grow: 1; }
        
        .nav-category {
            display: block;
            margin: 20px 0 10px 10px;
            font-size: 0.8rem;
            font-weight: bold;
            color: #64748b;
        }

        nav a {
            color: #94a3b8;
            text-decoration: none;
            display: flex;
            align-items: center;
            padding: 10px 15px;
            border-radius: 8px;
            transition: 0.3s;
            margin-bottom: 5px;
        }

        nav a:hover, nav a.active {
            background: var(--accent-blue);
            color: white;
        }

        .nav-footer {
            border-top: 1px solid rgba(255, 255, 255, 0.1);
            padding-top: 15px;
            margin-top: auto;
        }

        /* Bloque de Contenido (Default) */
        main {
            margin-left: 260px;
            padding: 3rem;
            flex-grow: 1;
            min-width: 0;
            display: flex;
            flex-direction: column;
        }

        header {
            text-align: center;
            margin-bottom: 3rem;
        }

        header h2 {
            font-size: 3rem;
            margin: 0;
            background: linear-gradient(to right, #fff, #60a5fa);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        /* Grid Forzado a 3 Columnas */
        .fixed-3-grid {
            display: grid;
            grid-template-columns: repeat(3, 1fr); /* FORZA 3 COLUMNAS FIJAS */
            gap: 25px;
            margin-bottom: 50px;
        }

        .card {
            background: var(--card-bg);
            border: 1px solid rgba(255, 255, 255, 0.1);
            padding: 2.5rem; /* Más espacio interior */
            border-radius: 20px;
            text-align: center;
            position: relative;
            transition: 0.4s;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 250px; /* Asegura altura uniforme */
        }

        .card:hover { 
            transform: translateY(-10px); 
            border-color: var(--accent-blue);
            background: rgba(59, 130, 246, 0.05);
        }

        .card i { font-size: 3rem; color: var(--light-blue); margin-bottom: 1.5rem; }
        .card h3 { margin: 10px 0; font-size: 1.5rem; }

        .badge { 
            position: absolute; 
            top: 15px; 
            right: 15px; 
            padding: 4px 10px; 
            border-radius: 20px; 
            font-size: 0.7rem; 
            text-transform: uppercase;
            font-weight: bold;
        }

        .badge-riesgo { background: var(--badge-riesgo); color: white; }
        .badge-medida { background: var(--badge-medida); color: black; } /* Negro para legibilidad */

        #referencias {
            margin-top: 2rem;
            background: rgba(255, 255, 255, 0.02);
            padding: 2.5rem;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .ref-list { color: #94a3b8; line-height: 1.8; margin-top: 15px; }
        
        .contenido-detalle {
            background: rgba(255, 255, 255, 0.05);
            padding: 40px;
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.1);
            line-height: 1.8;
        }
        .section-title {
            color: #60a5fa;
            border-left: 4px solid #3b82f6;
            padding-left: 15px;
            margin: 30px 0 15px 0;
        }
        .back-btn {
            display: inline-block;
            margin-bottom: 20px;
            color: #60a5fa;
            text-decoration: none;
            transition: 0.3s;
        }
        .back-btn:hover { color: white; transform: translateX(-5px); }
        ul li { margin-bottom: 10px; color: var(--text-color); line-height: 1.8; }
        ul li strong {color: #ffffff; font-weight: 600;}
    </style>
</head>
<body>

    <nav>
        <h1>Salud & IT</h1>
        <ul>
            <li><a href="index.html"><i class="fas fa-home"></i> &nbsp; Inicio</a></li>
            <span class="nav-category">1. RIESGOS</span>
            <li><a href="#"><i class="fas fa-bone"></i> &nbsp; T. Físicos</a></li>
            <li><a href="fatiga-visual.html" class="active"><i class="fas fa-eye"></i> &nbsp; Fatiga Visual</a></li>
            <li><a href="#"><i class="fas fa-brain"></i> &nbsp; Carga Mental</a></li>
            <span class="nav-category">2. PREVENCIÓN</span>
            <li><a href="#"><i class="fas fa-chair"></i> &nbsp; Diseño Puesto</a></li>
            <li><a href="#"><i class="fas fa-walking"></i> &nbsp; Pausas</a></li>
            <li><a href="#"><i class="fas fa-leaf"></i> &nbsp; Higiene</a></li>
        </ul>
        <div class="nav-footer">
            <a href="#referencias"><i class="fas fa-book"></i> &nbsp; Referencias</a>
        </div>
    </nav>

    <main>
        <a href="index.html" class="back-btn"><i class="fas fa-arrow-left"></i> Volver al inicio</a>
        
        <header>
            <h2>Fatiga Visual</h2>
            <p style="color: #94a3b8;">Riesgos derivados del trabajo prolongado con PVD (Pantallas de Visualización de Datos)</p>
        </header>

        <div class="contenido-detalle">
            <h3 class="section-title">¿Qué es?</h3>
            <p>La fatiga visual es la respuesta del ojo frente al esfuerzo muscular excesivo durante largos periodos de tiempo. En el entorno IT, se produce principalmente por el enfoque constante a una distancia corta y la exposición a contrastes lumínicos inadecuados.</p>

            <h3 class="section-title">Principales Síntomas</h3>
            <ul>
                <li><strong>Oculares:</strong> Escozor, enrojecimiento, sensación de arenilla y sequedad.</li>
                <li><strong>Visuales:</strong> Visión borrosa temporal, dificultad para enfocar objetos lejanos al terminar la jornada.</li>
                <li><strong>Extraoculares:</strong> Dolor de cabeza, vértigos y dolor cervical.</li>
            </ul>

            <h3 class="section-title">Medidas Preventivas</h3>
            <ul>
                <li><strong>Regla 20-20-20:</strong> Cada 20 minutos, apartar la vista de la pantalla durante 20 segundos enfocando a algo situado a 20 pies (unos 6 metros).</li>
                <li><strong>Iluminación:</strong> Evitar reflejos en la pantalla. La luz ambiental debe ser más tenue que la de la pantalla.</li>
                <li><strong>Ergonomía:</strong> La pantalla debe estar a unos 50-60 cm de distancia y a la altura de los ojos (o ligeramente por debajo).</li>
                <li><strong>Parpadeo:</strong> Forzar el parpadeo consciente para evitar la sequedad ocular.</li>
            </ul>
        </div>
    </main>

</body>
</html>
