---
layout: page
title: Archivo Punto Final
---

<!-- Imagen de portada -->
<img src="{{ '/assets/img/fondo-punto-final.jpg' | relative_url }}" 
     alt="Imagen de portada Punto Final" 
     class="img-fluid rounded shadow mb-4">

<!-- Contenido de la página -->
{% include index/description.html %}
{% include index/carousel.html title="Documentos Destacados" height="300" %}
{% include index/time.html %}
{% include index/featured-terms.html field="subject" title="Temas Principales" btn-color="primary" %}
{% include index/featured-terms.html field="location" title="Ubicaciones" btn-color="outline-secondary" %}
{% include index/objects.html %}
{% include index/data-download.html %}


