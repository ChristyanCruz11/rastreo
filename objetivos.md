---
layout: single
title: "Objetivos del Proyecto"
permalink: /resultados/
classes: wide

# DEFINICIÓN DE TARJETAS (OBJETIVOS / RESULTADOS ESPERADOS)
objetivos_row:
  - image_path: /rastreo/assets/img/ob_1.png
    alt: "Simulación"
    title: "1. Simulación y Entornos Hiperrealistas"
    excerpt: "Creación de entornos virtuales de desastre utilizando **IA generativa** y simuladores avanzados (NVIDIA Isaac Sim). Entrenamiento de la brigada en estrategias de exploración y colaboración multi-agente antes del despliegue."
  
  - image_path: /rastreo/assets/img/ob_2.png
    alt: "Control y Asistencia"
    title: "2. Asistencia Humanoide Inteligente"
    excerpt: "Desarrollo de un sistema de control robusto mediante **Aprendizaje por Refuerzo (RL)**. El robot humanoide aprenderá a manipular objetos, retirar escombros y asistir directamente a víctimas (respiradores, provisiones) en entornos hostiles."
  
  - image_path: /rastreo/assets/img/ob_3.png
    alt: "Validación Real"
    title: "3. Validación Sim-to-Real"
    excerpt: "Transferencia del aprendizaje simulado al mundo físico. Ejecución de pruebas y simulacros en el **CAR-Arena** y validación con equipos de rescate para demostrar la eficacia de la brigada mixta humanoide-cuadrúpedo."

---

## Impacto Esperado

La creciente incidencia de desastres naturales evidencia la necesidad urgente de optimizar las capacidades de búsqueda y rescate. **RASTREO** propone una solución tecnológica disruptiva: una **Brigada Robotizada** que combina la agilidad de los **robots cuadrúpedos** con la capacidad de manipulación de los **robots humanoides**.

---

## Objetivos y Resultados Científicos

El proyecto se estructura en tres pilares fundamentales que abarcan desde la simulación avanzada hasta la validación en escenarios reales:

{% include feature_row id="objetivos_row" %}

---

## Metodología de Validación

El proyecto utiliza una metodología innovadora basada en **Transfer Learning Sim-to-Real**. Al entrenar a los agentes en entornos virtuales seguros pero caóticos (generados procedimentalmente), la IA puede aprender de millones de iteraciones. Posteriormente, estas políticas de comportamiento se refinan y transfieren a los robots físicos para operar con precisión en el mundo real.
