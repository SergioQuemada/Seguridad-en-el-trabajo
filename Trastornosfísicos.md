<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salud Laboral IT - Trastornos Físicos</title>
    <style>
        /* VARIABLES DE DISEÑO PRO */
        :root {
            --bg-dark: #0d1117;
            --card-bg: #161b22;
            --text-main: #c9d1d9;
            --accent-blue: #58a6ff;
            --accent-purple: #bc85ff;
            --accent-red: #ff7b72;
            --border-color: #30363d;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-dark);
            color: var(--text-main);
            margin: 0;
            padding: 40px 20px;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
        }

        /* RECUADRO DE TÍTULO CON DEGRADADO */
        .header-box {
            border: 6px solid;
            border-image: linear-gradient(45deg, var(--accent-blue), var(--accent-purple), var(--accent-red)) 1;
            padding: 40px 20px;
            text-align: center;
            background: rgba(22, 27, 34, 0.8);
            margin-bottom: 50px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.5);
        }

        h1 {
            font-size: 2.8rem;
            color: #ffffff;
            margin: 0;
            text-transform: uppercase;
            letter-spacing: 3px;
        }

        .subtitle {
            font-size: 1.2rem;
            color: var(--accent-blue);
            margin-top: 10px;
            font-weight: 300;
        }

        /* SECCIONES */
        section {
            background: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 12px;
            padding: 30px;
            margin-bottom: 30px;
            transition: transform 0.3s ease, border-color 0.3s ease;
        }

        section:hover {
            transform: translateY(-5px);
            border-color: var(--accent-purple);
        }

        h2 {
            font-size: 1.8rem;
            color: var(--accent-blue);
            margin-top: 0;
            border-bottom: 1px solid var(--border-color);
            padding-bottom: 10px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        li {
            padding: 10px 0;
            display: flex;
            align-items: center;
        }

        li::before {
            content: "➜";
            margin-right: 15px;
            color: var(--accent-red);
        }

        /* TABLA COMPARATIVA */
        .table-wrap {
            overflow-x: auto;
            margin: 40px 0;
        }

        table {
            width: 100%;
            border-collapse: collapse;
            background: var(--card-bg);
            border-radius: 8px;
            overflow: hidden;
        }

        th {
            background-color: #21262d;
            color: #ffffff;
            padding: 15px;
            text-align: left;
            border-bottom: 2px solid var(--accent-purple);
        }

        td {
            padding: 15px;
            border-bottom: 1px solid var(--border-color);
        }

        tr:hover {
            background-color: #1f242c;
        }

        /* NAVEGACIÓN INFERIOR */
        footer {
            display: flex;
            justify-content: space-between;
            margin-top: 60px;
            padding-top: 20px;
            border-top: 1px solid var(--border-color);
        }

        .nav-link {
            text-decoration: none;
            color: #ffffff;
            background: #21262d;
            padding: 12px 25px;
            border-radius: 50px;
            border: 1px solid var(--border-color);
            font-weight: bold;
            transition: all 0.3s ease;
            display: flex;
            align-items: center;
        }

        .nav-link:hover {
            background: var(--accent-blue);
            border-color: #ffffff;
            transform: scale(1.05);
        }

        .arrow { font-size: 1.4rem; }
        .m-right { margin-right: 10px; }
        .m-left { margin-left: 10px; }

    </style>
</head>
<body>

<div class="container">
    <header class="header-box">
        <h1>Trastornos Físicos</h1>
        <div class="subtitle">Riesgos Derivados del Trabajo Informático</div>
    </header>

    <section>
        <h2>🔹 Dolor de Cuello y Cervicales</h2>
        <p>Aparece por mantener posturas estáticas o forzadas durante la jornada.</p>
        <ul>
            <li>Pantallas colocadas a una altura incorrecta.</li>
            <li>Girar el cuello constantemente hacia un lado para mirar el monitor.</li>
            <li>Uso excesivo de dispositivos móviles sin soporte.</li>
        </ul>
    </section>

    <section>
        <h2>🔹 Hombros y Espalda Alta</h2>
        <p>Se manifiesta como tensión en la zona escapular y trapecios.</p>
        <ul>
            <li>No apoyar correctamente los antebrazos en la mesa.</li>
            <li>Mesas demasiado elevadas que fuerzan la subida de hombros.</li>
            <li>Ratón o teclado alejados del cuerpo.</li>
        </ul>
    </section>

    <div class="table-wrap">
        <table>
            <thead>
                <tr>
                    <th>Zona</th>
                    <th>Factor de Riesgo</th>
                    <th>Consecuencia</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Lumbar</td>
                    <td>Silla sin apoyo adecuado</td>
                    <td>Sobrecarga vertebral</td>
                </tr>
                <tr>
                    <td>Muñecas</td>
                    <td>Movimientos repetitivos</td>
                    <td>Síndrome del Túnel Carpiano</td>
                </tr>
                <tr>
                    <td>Piernas</td>
                    <td>Falta de movimiento</td>
                    <td>Problemas circulatorios</td>
                </tr>
            </tbody>
        </table>
    </div>

    <section>
        <h2>🔹 Espalda y Zona Lumbar</h2>
        <p>El sedentarismo prolongado es el mayor enemigo de nuestra columna.</p>
        <ul>
            <li>Inclinación del tronco hacia adelante o hacia los lados.</li>
            <li>Sillas demasiado rígidas o sin ajuste de profundidad.</li>
            <li>Falta de cambios de postura (micro-pausas).</li>
        </ul>
    </section>

    <section>
        <h2>🔹 Manos, Muñecas y Piernas</h2>
        <p>Afecta a la movilidad fina y a la circulación de retorno.</p>
        <ul>
            <li>Posiciones forzadas de la muñeca (hacia arriba o hacia abajo).</li>
            <li>Presión en la parte posterior de la rodilla por sillas altas.</li>
            <li>Entumecimiento por falta de apoyo firme de los pies.</li>
        </ul>
    </section>

    <footer>
        <a href="#" class="nav-link">
            <span class="arrow m-right">←</span> Volver al menú principal
        </a>
        <a href="#" class="nav-link">
            Fatiga visual <span class="arrow m-left">→</span>
        </a>
    </footer>
</div>

</body>
</html>
