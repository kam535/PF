---
layout: default
title: Archivo Punto Final
---
<img src="assets/img/fondo-punto-final.jpg" alt="Imagen de portada Punto Final" style="width:100%; max-height:500px; object-fit:cover; margin-bottom:20px;">
<img src="assets/img/fondo-punto-final.jpg" alt="Imagen portada Punto Final" style="width:100%; max-height:600px; object-fit:cover; margin-bottom: 2rem;">

<div class="row">
  <div class="col-md-8">
    {% include index/description.html %}
    {% include index/carousel.html title="Documentos Destacados" height="300" %}
  </div>
  <div class="col-md-4">  
    {% include index/time.html %}
    {% include index/featured-terms.html field="subject" title="Temas Principales" btn-color="primary" %}
    {% include index/featured-terms.html field="location" title="Ubicaciones" btn-color="outline-secondary" %}
    {% include index/objects.html %}
  </div>
  <div class="col-md-12">
    {% include index/data-download.html %}
  </div>
</div>

