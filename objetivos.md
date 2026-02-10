---
layout: splash
title: "Objetivos del Proyecto"
permalink: /objetivos/

# --- CABECERA ESTILO PORTADA (LO QUE FALTABA) ---
header:
  overlay_image: /rastreo/assets/img/leonardo_1.jpeg
  overlay_filter: 0.4
  caption: "Créditos: RASTREO Team"
excerpt: >
  Nuestra hoja de ruta científica: desde la simulación hiperrealista hasta la validación en escenarios de desastre real.

# --- TARJETAS DE OBJETIVOS ---
objetivos_row:
  - image_path: /assets/img/ob_1.png
    alt: "Simulación"
    title: "1. Simulación Hiperrealista"
    excerpt: "Entrenamiento en **entornos virtuales** generados con IA y NVIDIA Isaac Sim para aprender estrategias de exploración seguras."
  
  - image_path: /assets/img/ob_2.png
    alt: "Control y Asistencia"
    title: "2. Asistencia Inteligente"
    excerpt: "Control del robot humanoide mediante **Aprendizaje por Refuerzo** para manipular escombros y entregar ayuda a víctimas."
  
  - image_path: /assets/img/ob_3.png
    alt: "Validación Real"
    title: "3. Validación Sim-to-Real"
    excerpt: "Pruebas de campo en el **CAR-Arena** y simulacros con rescatistas para validar la transferencia de aprendizaje."
---

{% include feature_row id="objetivos_row" %}

<section class="page__content" style="margin-top: 3rem;">
  
  <div class="notice--info">
    <h4 class="no_toc">Impacto del Proyecto</h4>
    <p>
      El objetivo final de <strong>RASTREO</strong> es reducir los tiempos de respuesta en catástrofes. 
      Al combinar la agilidad de los cuadrúpedos con la destreza manual de los humanoides, 
      protegemos a los rescatistas humanos y aumentamos las probabilidades de supervivencia de las víctimas.
    </p>
  </div>

  <h2>Metodología de Trabajo</h2>
  <p>
    Utilizamos una metodología cíclica de <strong>Sim-to-Real</strong>. Los algoritmos se entrenan millones de veces en simulaciones 
    paralelizadas (Objetivo 1 y 2) antes de ser transferidos al hardware físico (Objetivo 3), garantizando seguridad y robustez.
  </p>

</section>
