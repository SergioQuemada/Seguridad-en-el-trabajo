---
layout: default
title: Inicio - PRL
---

<style>
  .hero-card {
    background: linear-gradient(120deg, #2e7d32 0%, #004d40 100%);
    color: white;
    padding: 60px;
    border-radius: 24px;
    text-align: center;
    margin-bottom: 40px;
    box-shadow: 0 20px 40px rgba(0,0,0,0.3);
  }
  .hero-card h1 { color: white !important; font-size: 2.8rem; margin: 0; }
  .hero-card p { color: rgba(255,255,255,0.9) !important; margin-top: 15px; font-size: 1.2rem; }

  .grid-indice {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
    gap: 20px;
  }

  .card-item {
    background: white;
    padding: 30px;
    border-radius: 20px;
    text-decoration: none !important;
    text-align: center;
    transition: 0.3s;
    border: 1px solid #e2e8f0;
  }
  .card-item:hover { transform: translateY(-10px); border-color: #2e7d32; box-shadow: 0 10px 25px rgba(0,0,0,0.1); }
  .card-icon { font-size: 45px; margin-bottom: 15px; display: block; }
  .card-title { font-weight: bold; color: #0f172a; font-size: 1.2rem; margin-bottom: 10px; display: block; }
  .card-desc { color: #64748b; font-size: 0.95rem; line-height: 1.5; display: block; }
</style>

<div class="hero-card">
  <h1>Prevención de Riesgos Laborales</h1>
  <p>Sergio Quemada, Mario Infantes y Álvaro Zarza</p>
</div>

<div class="grid-indice">
  <a href="trastornos-musculoesqueleticos.html" class="card-item">
    <span class="card-icon">🦴</span>
    <span class="card-title">Trastornos Físicos</span>
    <span class="card-desc">Análisis de lesiones músculo-esqueléticas y ergonomía física.</span>
  </a>

  <a href="fatiga-visual.html" class="card-item">
    <span class="card-icon">👁️</span>
    <span class="card-title">Fatiga Visual</span>
    <span class="card-desc">Riesgos derivados del uso prolongado de pantallas y PVD.</span>
  </a>

  <a href="tecnoestres.html" class="card-item">
    <span class="card-icon">🧠</span>
    <span class="card-title">Carga Mental y Estrés</span>
    <span class="card-desc">Impacto psicológico y estrés en el entorno informático.</span>
  </a>

  <a href="ergonomia-puesto.html" class="card-item">
    <span class="card-icon">💺</span>
    <span class="card-title">Diseño del Puesto</span>
    <span class="card-desc">Organización óptima del espacio de trabajo y mobiliario.</span>
  </a>
</div>
