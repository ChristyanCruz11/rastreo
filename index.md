---
layout: splash
title: "RASTREO — Brigada Robotizada Inteligente de Búsqueda y Rescate"
permalink: /
# Cabecera con imagen de portada (hero)
header:
  # IMPORTANTE: como tu sitio es de proyecto, anteponemos /rastreo al path
  overlay_image: /rastreo/assets/img/leonardo_1.jpeg
  overlay_filter: 0.30          # 0.0 = sin filtro, 1.0 = negro opaco sobre la imagen
  actions:
    - label: "Ver el proyecto"
      url: "/rastreo/proyecto/"
    - label: "Contacto"
      url: "/rastreo/contacto/"
excerpt: >
  Brigada mixta humanoide–cuadrúpedos con IA avanzada, simulación hiperrealista y validación <em>Sim‑to‑Real</em> para búsqueda y rescate en escenarios de desastre.
# Metadatos opcionales para SEO
# description: "Proyecto RASTREO — Beca Leonardo 2024 (Fundación BBVA)."
---

{% include feature_row id="features" %}

<section class="page__content" style="margin-top:2rem;">
  <h2>¿Qué es RASTREO?</h2>
  <p>
    <strong>RASTREO</strong> desarrolla una brigada robotizada que combina robots cuadrúpedos y un robot humanoide de última generación para
    <strong>explorar entornos pos‑desastre</strong> y <strong>asistir directamente a víctimas</strong>. El sistema integra percepción multimodal (RGB‑D, LiDAR),
    <strong>IA</strong> (aprendizaje por refuerzo, coordinación multi‑agente) y <em>simulaciones hiperrealistas</em> para entrenar y validar políticas antes del despliegue real.
  </p>

  <h3>Objetivo general</h3>
  <p>
    Implementar una <strong>Brigada Robotizada</strong> humanoide–cuadrúpedos capaz de reducir tiempos de respuesta y riesgos para equipos humanos, aumentando la
    probabilidad de rescate con vida mediante <em>exploración coordinada</em> y <strong>asistencia segura</strong> a víctimas.
  </p>

  <h3>Objetivos específicos</h3>
  <ul>
    <li><strong>O1:</strong> Entornos virtuales hiperrealistas con IA generativa para entrenar colaboración y manipulación.</li>
    <li><strong>O2:</strong> Control seguro de asistencia en humanoide (impedancia, contacto) entrenado con aprendizaje por refuerzo.</li>
    <li><strong>O3:</strong> Validación <em>Sim‑to‑Real</em>, demostradores, publicaciones y difusión social.</li>
  </ul>

  <p style="margin-top:1rem;">
    <a class="btn btn--primary" href="/rastreo/proyecto/">Leer detalles del proyecto</a>
    <a class="btn" href="/rastreo/resultados/" style="margin-left:.5rem;">Ver resultados</a>
  </p>

  <hr>

  <h3>Menciones obligatorias</h3>
  <p>
    “Proyecto realizado con la Beca Leonardo de Investigación Científica y Creación Cultural 2024 de la Fundación BBVA”.<br>
    “La Fundación no se responsabiliza de las opiniones, comentarios y contenidos incluidos en el proyecto, los cuales son total y absoluta responsabilidad de sus autores”.
  </p>
</section>

{% comment %}
  Bloque de tarjetas destacadas (debajo del hero).
  Minimal Mistakes espera una variable de página llamada "feature_row" (o el ID que indiquemos)
  y luego usamos {% include feature_row id="features" %} arriba.
{% endcomment %}

{: .hidden}
features:
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
