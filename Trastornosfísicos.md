<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trastornos Físicos - Sector Informático</title>
    <style>
        /* --- ESTILO GENERAL --- */
        body {
            font-family: "Segoe UI", Arial, sans-serif;
            line-height: 1.7;
            color: #222;
            background-color: #f4f7f9;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: white;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.08);
        }

        /* --- TÍTULO PRINCIPAL (Estilo Degradado) --- */
        .header-banner {
            text-align: center;
            padding: 30px;
            border-radius: 12px;
            background: linear-gradient(90deg, #d9534f, #f0ad4e); /* Tonos cálidos para salud */
            color: white;
            margin-bottom: 30px;
        }

        /* --- TARJETAS ECO-STYLE --- */
        .eco-card {
            background: #ffffff;
            border-radius: 14px;
            padding: 25px;
            border: 1px solid #dfe3e8;
            box-shadow: 0 6px 18px rgba(0,0,0,0.06);
            transition: 0.3s ease;
            margin-bottom: 25px;
        }

        .eco-card:hover {
            transform: translateY(-6px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.12);
        }

        /* Colores de borde para categorías */
        .eco-red { border-left: 8px solid #d9534f; }    /* Cuello/Espalda */
        .eco-blue { border-left: 8px solid #007bff; }   /* Extremidades */
        .eco-yellow { border-left: 8px solid #f0ad4e; } /* General */
        .eco-green { border-left: 8px solid #28a745; }  /* Conclusión */

        .eco-title {
            font-size: 1.4em;
            font-weight: bold;
            margin-bottom: 12px;
            display: flex;
            align-items: center;
        }

        /* --- ESTILO DE TABLAS --- */
        .tabla-eco {
            width: 100%;
            border-collapse: collapse;
            margin: 25px 0;
            font-size: 1em;
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 4px 12px rgba(0,0,0,0.05);
        }

        .tabla-eco thead tr {
            background: #d9534f;
            color: white;
            text-align: left;
        }

        .tabla-eco th, .tabla-eco td {
            padding: 14px 18px;
            border-bottom: 1px solid #e9ecef;
        }

        .tabla-eco tbody tr:nth-child(even) {
            background: #f8f9fa;
        }

        /* --- NAVEGACIÓN INFERIOR --- */
        .nav-container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
        }

        .btn-nav {
            text-decoration: none;
            color: #d9534f;
            font-weight: bold;
            font-size: 1.1em;
            transition: 0.3s;
        }

        .btn-nav:hover {
            color: #b52b27;
            text-decoration: underline;
        }

    </style>
</head>
<body>

<div class="container">

    <header class="header-banner">
        <h1 style="margin: 0; font-size: 2.3em;">Trastornos Físicos en IT</h1>
        <p style="margin: 5px 0 0 0; opacity: 0.9;">Riesgos derivados del trabajo prolongado con ordenadores</p>
    </header>

    <p>El trabajo prolongado con ordenadores puede generar diversos trastornos musculoesqueléticos por posturas incorrectas, equipos mal ajustados o movimientos repetitivos.</p>

    <div class="eco-card eco-red">
        <div class="eco-title">🔹 Dolor de Cuello</div>
        <p>Aparece cuando el trabajador mantiene el cuello girado, flexionado o extendido durante largos periodos.</p>
        <ul style="margin-top: 10px;">
            <li>Pantallas colocadas demasiado altas o bajas.</li>
            <li>Monitores situados a un lado, obligando a girar la cabeza.</li>
            <li>Posturas mantenidas sin descanso.</li>
        </ul>
    </div>

    <div class="eco-card eco-red">
        <div class="eco-title">🔹 Molestias en Hombros y Espalda</div>
        <p>La postura sentada durante muchas horas provoca carga en las vértebras, ligamentos y musculatura.</p>
        <ul>
            <li>Falta de apoyo lumbar adecuado.</li>
            <li>Mesa demasiado alta (eleva los hombros).</li>
            <li>Inclinaciones del tronco hacia adelante.</li>
        </ul>
    </div>

    <table class="tabla-eco">
        <thead>
            <tr>
                <th>Zona Afectada</th>
                <th>Causa Frecuente</th>
                <th>Riesgo</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Muñecas</td>
                <td>Uso repetitivo del ratón</td>
                <td>Túnel Carpiano</td>
            </tr>
            <tr>
                <td>Piernas</td>
                <td>Silla alta o mala posición</td>
                <td>Mala circulación</td>
            </tr>
            <tr>
                <td>General</td>
                <td>Postura estática</td>
                <td>Fatiga muscular</td>
            </tr>
        </tbody>
    </table>

    <div class="eco-card eco-blue">
        <div class="eco-title">🔹 Molestias en Manos y Muñecas</div>
        <p>Se deben al mantenimiento de la muñeca en posiciones forzadas o movimientos repetitivos intensos.</p>
        <ul>
            <li>Teclados demasiado altos o inclinados.</li>
            <li>Uso excesivo del ratón sin alfombrilla ergonómica.</li>
            <li>Tareas intensivas de introducción de datos.</li>
        </ul>
    </div>

    <div class="eco-card eco-yellow">
        <div class="eco-title">🔹 Entumecimiento en Piernas</div>
        <p>Permanecer sentado mucho tiempo provoca presión en la parte posterior de las rodillas y mala circulación.</p>
    </div>

    <div class="eco-card eco-green">
        <div class="eco-title">En Resumen...</div>
        <p>Los trastornos físicos en el sector informático se deben principalmente a <strong>posturas inadecuadas</strong> y <strong>permanencia prolongada</strong>. La prevención mediante pausas y ergonomía es fundamental.</p>
    </div>

    <div class="nav-container">
        <a href="index.html" class="btn-nav">
            🏠 Volver a Menú Principal
        </a>
        <a href="fatiga-visual.html" class="btn-nav">
            Fatiga Visual ➜
        </a>
    </div>

</div>

</body>
</html>
