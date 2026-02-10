---
layout: single
title: "Contacto"
permalink: /contacto/
toc: false
classes: wide
---

<style>
/* Contenedor principal para centrar el contenido */
.contact-wrapper {
  max-width: 800px;
  margin: 0 auto;
}

/* Diseño de las tarjetas */
.contact-card {
  background: #fff;
  border: 1px solid rgba(0,0,0,0.1);
  border-radius: 12px;
  overflow: hidden; /* Para que la imagen respete los bordes redondeados */
  box-shadow: 0 4px 12px rgba(0,0,0,0.08);
  margin-bottom: 2.5rem;
  transition: transform 0.2s;
}

.contact-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 16px rgba(0,0,0,0.12);
}

/* Estilo de las imágenes horizontales */
.contact-banner {
  width: 100%;
  height: 280px; /* Altura fija para uniformidad */
  object-fit: cover; /* Recorta la imagen para llenar el espacio sin deformar */
  object-position: center;
  display: block;
  border-bottom: 1px solid #eee;
}

/* Contenido de texto */
.contact-info {
  padding: 2rem;
}

.contact-info h3 {
  margin-top: 0;
  color: #2c3e50;
  font-size: 1.4rem;
  margin-bottom: 0.5rem;
}

.contact-info h4 {
  font-size: 1.1rem;
  color: #555;
  margin-top: 0;
  margin-bottom: 1rem;
  font-weight: normal;
}

.info-item {
  display: flex;
  align-items: flex-start;
  margin-bottom: 0.8rem;
  font-size: 1rem;
  color: #444;
}

.info-item i {
  margin-right: 12px;
  color: #0056b3; /* Azul corporativo */
  margin-top: 4px;
}

.info-item a {
  text-decoration: none;
  color: #0056b3;
}
.info-item a:hover {
  text-decoration: underline;
}

/* Ajuste para móviles */
@media (max-width: 600px) {
  .contact-banner {
    height: 180px;
  }
  .contact-info {
    padding: 1.5rem;
  }
}
</style>

<div class="contact-wrapper">

  <div class="contact-card">
    <img src="/rastreo/assets/img/car.jpeg" alt="Edificio CAR UPM CSIC" class="contact-banner">
    
    <div class="contact-info">
      <h3>Centro de Automática y Robótica (UPM-CSIC)</h3>
      <h4>Sede Universidad Politécnica de Madrid</h4>
      
      <div class="info-item">
        <strong>Dirección:</strong>&nbsp; C. de José Gutiérrez Abascal, 2, 28006 Madrid
      </div>
      
      <div class="info-item">
        <strong>Teléfono:</strong>&nbsp; <a href="tel:+34910676900">910 67 69 00</a>
      </div>

      <div style="margin-top: 1.5rem;">
        <a href="https://www.google.com/maps/place/Centro+de+Autom%C3%A1tica+y+Rob%C3%B3tica+(UPM-CSIC)/@40.4394045,-3.6906928,17z/data=!3m1!4b1!4m6!3m5!1s0xd422904151b6ee1:0x808172ba7d95129!8m2!3d40.4394045!4d-3.6881125!16s%2Fg%2F11k548qkyc?entry=ttu&g_ep=EgoyMDI2MDIwNC4wIKXMDSoASAFQAw%3D%3D" target="_blank" class="btn btn--primary">Ver en Google Maps</a>
      </div>
    </div>
  </div>

  <div class="contact-card">
    <img src="/rastreo/assets/img/iros_3.PNG" alt="Christyan Cruz en IROS" class="contact-banner" style="object-position: top center;">
    
    <div class="contact-info">
      <h3>Christyan Cruz Ulloa</h3>
      <h4>Investigador Principal (IP)</h4>
      
      <div class="info-item">
        <strong>Email:</strong>&nbsp; <a href="mailto:christyan.cruz.ulloa@upm.es">christyan.cruz.ulloa@upm.es</a>
      </div>
       <div class="info-item">
        <strong>Afiliación:</strong>&nbsp; CAR-UPM-CSIC
      </div>
    </div>
  </div>

</div>
