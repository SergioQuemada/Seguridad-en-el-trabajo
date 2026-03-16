---
layout: default
title: Inicio - Salud e Informática
---

<style>
  /* Portada Estilo Hero */
  .hero-portada {
    background: linear-gradient(120deg, #2e7d32 0%, #004d40 100%);
    color: white;
    padding: 50px 30px;
    border-radius: 20px;
    text-align: center;
    margin-bottom: 40px;
    box-shadow: 0 10px 20px rgba(0,0,0,0.2);
  }

  .hero-portada h1 { color: white !important; margin: 0; font-size: 2.5rem; }
  .hero-portada p { color: #e0e0e0 !important; font-size: 1.1rem; margin-top: 10px; }

  /* Grid de Tarjetas */
  .grid-indice {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 20px;
  }

  .tarjeta-link {
    background: #ffffff;
    border: 1px solid #e2e8f0;
    border-radius: 15px;
    padding: 25px;
    text-decoration: none !important;
    transition: all 0.3s ease;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .tarjeta-link:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0,0,0,0.1);
    border-color: #2e7d32;
  }

  .t-icon { font-size: 40px; margin-bottom: 15px; }
  .t-title { font-weight: bold; color: #1e293b; margin-bottom: 8px; font-size: 1.1rem; }
  .t-desc { color: #64748b; font-size: 0.9rem; line-height: 1.4; }
</style>

<div class="hero-portada">
  <h1>Prevención de Riesgos en Informática</h1>
  <p>Análisis y soluciones para Sergio Quemada, Mario Infantes y Álvaro Zarza</p>
</div>

<div class="grid-indice">
  <a href="trastornos-musculoesqueleticos.html" class="tarjeta-link">
    <div class="t-icon">🦴</div>
    <div class="t-title">Trastornos Físicos</div>
    <div class="t-desc">Posturas, ergonomía y cómo cuidar tu espalda y manos.</div>
  </a>

  <a href="fatiga-visual.html" class="tarjeta-link">
    <div class="t-icon">👁️</div>
    <div class="t-title">Fatiga Visual</div>
    <div class="t-desc">Protege tus ojos del cansancio provocado por las pantallas.</div>
  </a>

  <a href="tecnoestres.html" class="tarjeta-link">
    <div class="t-icon">🧠</div>
    <div class="t-title">Carga Mental</div>
    <div class="t-desc">Gestión del estrés y desconexión digital para informáticos.</div>
  </a>

  <a href="ergonomia-puesto.html" class="tarjeta-link">
    <div class="t-icon">💺</div>
    <div class="t-title">Diseño del Puesto</div>
    <div class="t-desc">Configuración ideal de silla, mesa y periféricos.</div>
  </a>
</div>
