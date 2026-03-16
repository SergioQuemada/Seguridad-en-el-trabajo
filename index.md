---
layout: default
title: Inicio - Seguridad en el Trabajo
---

<style>
  /* --- CONTENEDOR PRINCIPAL --- */
  .main-container {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #2c3e50;
    max-width: 900px;
    margin: auto;
  }

  /* --- HEADER ESTILO HERO --- */
  .hero-section {
    background: linear-gradient(120deg, #1976d2 0%, #0d47a1 100%); /* Cambiado a Azul (seguridad) */
    color: white;
    padding: 60px 20px;
    border-radius: 20px;
    text-align: center;
    box-shadow: 0 10px 30px rgba(0,0,0,0.15);
    margin-bottom: 40px;
  }

  /* --- GRID DE NAVEGACIÓN --- */
  .grid-indice {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
    padding: 10px;
  }

  /* --- TARJETAS --- */
  .card {
    background: #ffffff;
    border: 1px solid #e0e0e0;
    border-radius: 15px;
    padding: 25px;
    text-decoration: none !important;
    color: #333 !important;
    transition: all 0.3s cubic-bezier(0.25, 0.8, 0.25, 1);
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

  .card:hover {
    transform: translateY(-10px);
    box-shadow: 0 15px 30px rgba(0,0,0,0.1);
    border-color: #1976d2; /* Borde azul al pasar el ratón */
  }

  .card-icon {
    font-size: 40px;
    margin-bottom: 15px;
  }

  .card-title {
    font-weight: bold;
    font-size: 1.2em;
    margin-bottom: 10px;
    color: #0d47a1;
  }

  .card-desc {
    font-size: 0.9em;
    color: #666;
  }

  /* --- PIE DE PÁGINA --- */
  .footer-info {
    margin-top: 50px;
    padding: 20px;
    border-top: 2px solid #eee;
    text-align: center;
    font-style: italic;
    color: #7f8c8d;
  }
</style>

<div class="main-container">

  <div class="hero-section">
    <h1 style="color: white; margin: 0; font-size: 2.8em;">Seguridad en el Trabajo</h1>
    <p style="color: white; font-size: 1.2em; opacity: 0.9; margin-top: 15px;">Prevención de riesgos y bienestar en el entorno laboral</p>
  </div>

  <div class="grid-indice">
    
    <a href="marco_legal.html" class="card">
      <div class="card-icon">⚖️</div>
      <div class="card-title">Marco Normativo</div>
      <div class="card-desc">Leyes y reglamentos básicos que garantizan la seguridad del trabajador.</div>
    </a>

    <a href="riesgos_comunes.html" class="card">
      <div class="card-icon">⚠️</div>
      <div class="card-title">Riesgos Laborales</div>
      <div class="card-desc">Identificación de peligros físicos, químicos y ergonómicos en el puesto.</div>
    </a>

    <a href="equipos_proteccion.html" class="card">
      <div class="card-icon">⛑️</div>
      <div class="card-title">Equipos de Protección (EPI)</div>
      <div class="card-desc">Uso correcto de cascos, guantes y material de seguridad individual.</div>
    </a>

    <a href="primeros_auxilios.html" class="card">
      <div class="card-icon">🚑</div>
      <div class="card-title">Primeros Auxilios</div>
      <div class="card-desc">Protocolos de actuación inmediata ante accidentes o emergencias médicas.</div>
    </a>

    <a href="bibliografia.html" class="card" style="grid-column: 1 / -1;">
      <div class="card-icon">📖</div>
      <div class="card-title">Fuentes y Documentación</div>
      <div class="card-desc">Bibliografía consultada y créditos del proyecto de seguridad.</div>
    </a>

  </div>

  <div class="footer-info">
    "La mejor herramienta de seguridad es la prevención."
    <br><strong>Proyecto: Seguridad y Salud Laboral</strong>
  </div>

</div>
