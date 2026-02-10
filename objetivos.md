---
layout: splash
title: "Objetivos del Proyecto"
permalink: /objetivos/

# --- CABECERA PRINCIPAL (IDÉNTICA A LA DE INICIO) ---
header:
  overlay_image: /rastreo/assets/img/leonardo_1.jpeg
  overlay_filter: 0.3 # Mismo filtro que en la home para que se vea igual
  caption: "Créditos: RASTREO Team"
excerpt: >
  Nuestra hoja de ruta científica: desde la simulación hiperrealista hasta la validación en escenarios de desastre real.
---

<style>
  .obj-banner {
    position: relative;
    width: 100%;
    padding: 6rem 2rem;
    margin-bottom: 2rem;
    background-size: cover;
    background-position: center;
    border-radius: 4px;
    box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    color: #fff;
    text-align: center;
    overflow: hidden;
  }
  
  .obj-overlay {
    position: absolute;
    top: 0; left: 0; right: 0; bottom: 0;
    /* CAMBIO AQUÍ: Bajado a 0.15 (15% de oscuridad) para que sean muy claras */
    background: rgba(0, 0, 0, 0.15); 
    z-index: 1;
  }
  
  .obj-content {
    position: relative;
    z-index: 2;
    max-width: 900px;
    margin: 0 auto;
  }

  .obj-content h2 {
    color: #fff;
    font-size: 2.5rem;
    margin-bottom: 1rem;
    text-transform: uppercase;
    /* Sombra fuerte para que el texto se lea bien sobre la foto clara */
    text-shadow: 2px 2px 8px rgba(0,0,0,0.9);
    border-bottom: 2px solid rgba(255,255,255,0.6);
    display: inline-block;
    padding-bottom: 10px;
  }

  .obj-content p {
    font-size: 1.25rem;
    line-height: 1.6;
    color: #fff;
    font-weight: 500;
    text-shadow: 1px 1px 6px rgba(0,0,0,1);
  }
</style>

<div class="obj-banner" style="background-image: url('/rastreo/assets/img/ob_1.png');">
  <div class="obj-overlay"></div>
  <div class="obj-content">
    <h2>1. Simulación Hiperrealista</h2>
    <p>
      Creación de <strong>entornos virtuales de desastre</strong> utilizando IA generativa y simuladores avanzados (NVIDIA Isaac Sim).<br>
      Entrenamos a la brigada en estrategias de exploración y colaboración multi-agente en un mundo digital seguro antes de pisar el mundo real.
    </p>
  </div>
</div>

<div class="obj-banner" style="background-image: url('/rastreo/assets/img/ob_2.png');">
  <div class="obj-overlay"></div>
  <div class="obj-content">
    <h2>2. Asistencia Inteligente</h2>
    <p>
      Desarrollo de control robusto mediante <strong>Aprendizaje por Refuerzo (RL)</strong>.<br>
      Dotamos al robot humanoide de la capacidad para manipular escombros, abrir puertas y entregar asistencia vital (respiradores, provisiones) directamente a las víctimas.
    </p>
  </div>
</div>

<div class="obj-banner" style="background-image: url('/rastreo/assets/img/ob_3.png');">
  <div class="obj-overlay"></div>
  <div class="obj-content">
    <h2>3. Validación Sim-to-Real</h2>
    <p>
      El paso definitivo: transferir el "cerebro" entrenado en simulación al cuerpo físico.<br>
      Ejecución de pruebas de campo en el <strong>CAR-Arena</strong> y simulacros conjuntos con rescatistas para validar la eficacia real de la brigada.
    </p>
  </div>
</div>

<section class="page__content" style="margin-top: 4rem;">
  
  <div class="notice--info">
    <h4 class="no_toc">Impacto del Proyecto</h4>
    <p>
      El objetivo final de <strong>RASTREO</strong> es reducir los tiempos de respuesta en catástrofes. 
      Al combinar la agilidad todo-terreno de los cuadrúpedos con la destreza manual de los humanoides, 
      protegemos a los rescatistas humanos y aumentamos drásticamente las probabilidades de supervivencia.
    </p>
  </div>

</section>
