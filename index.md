---
layout: splash
title: "RASTREO — Brigada Robotizada Inteligente de Búsqueda y Rescate"
permalink: /

# Cabecera con imagen (rutas absolutas porque baseurl=/rastreo)
header:
  overlay_image: /rastreo/assets/img/leonardo_1.jpeg
  overlay_filter: 0.30
  actions:
    - label: "Ver el proyecto"
      url: "/rastreo/proyecto/"
    - label: "Equipo"
      url: "/rastreo/equipo/"
excerpt: >
  Brigada mixta humanoide–cuadrúpedos con IA avanzada, simulación hiperrealista y validación <em>Sim‑to‑Real</em> para búsqueda y rescate en escenarios de desastre.

# Tarjetas (deben ir en el front matter)
feature_row:
  - image_path: /rastreo/assets/img/leonardo_1.jpeg
    alt: "Proyecto"
    title: "Proyecto"
    excerpt: "Objetivos, motivación, hipótesis y metodología."
    url: "/rastreo/proyecto/"
    btn_label: "Leer más"
    btn_class: "btn--primary"
  - image_path: /rastreo/assets/img/leonardo_1.jpeg
    alt: "Resultados"
    title: "Resultados"
    excerpt: "Demos, vídeos, publicaciones y validación Sim‑to‑Real."
    url: "/rastreo/resultados/"
    btn_label: "Ver avances"
    btn_class: "btn--primary"
  - image_path: /rastreo/assets/img/leonardo_1.jpeg
    alt: "Difusión"
    title: "Difusión"
    excerpt: "Apariciones en medios, notas de prensa y divulgación."
    url: "/rastreo/difusion/"
    btn_label: "Ver difusión"
    btn_class: "btn--primary"
---

{% include feature_row %}

<section class="page__content" style="margin-top:2rem;">
  <h2>¿Qué es RASTREO?</h2>
  <p>
    <strong>RASTREO</strong> desarrolla una brigada robotizada que combina robots cuadrúpedos y un robot humanoide de última generación para
    <strong>explorar entornos pos‑desastre</strong> y <strong>asistir directamente a víctimas</strong>. Integra percepción multimodal (RGB‑D, LiDAR),
    <strong>IA</strong> (aprendizaje por refuerzo, coordinación multi‑agente) y <em>simulaciones hiperrealistas</em> para entrenar y validar políticas antes del despliegue real.
  </p>
</section>

<!-- Menciones BBVA como badge flotante, discreto en la esquina -->
<div class="bbva-badge">
  <small>
    “Proyecto realizado con la Beca Leonardo de Investigación Científica y Creación Cultural 2024 de la Fundación BBVA”.<br>
    “La Fundación no se responsabiliza de las opiniones, comentarios y contenidos incluidos en el proyecto, los cuales son total y absoluta responsabilidad de sus autores”.
  </small>
</div>

<style>
/* Caja flotante discreta en esquina inferior derecha */
.bbva-badge{
  position: fixed;
  right: 10px;
  bottom: 10px;
  max-width: 320px;
  background: rgba(255,255,255,0.92);
  border: 1px solid rgba(0,0,0,0.06);
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  border-radius: 8px;
  padding: 8px 10px;
  z-index: 9999;
  font-size: 12px;
  line-height: 1.3;
}
@media (max-width: 768px){
  .bbva-badge{ max-width: 86vw; right: 8px; left: 8px; }
}
</style>
