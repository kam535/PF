---
layout: page
title: Archivo Punto Final
---

<!-- Imagen de portada -->
<img src="{{ '/assets/img/fondo-punto-final.jpg' | relative_url }}" 
     alt="Imagen de portada Punto Final" 
     class="img-fluid rounded shadow mb-4">

<!-- Contenido de la página -->
<div class="text-center my-4">
  <img src="{{ 'assets/img/fondo-punto-final.jpg' | relative_url }}"
       alt="Portada de Punto Final"
       class="img-fluid rounded shadow-lg w-75">
</div>

# Archivo digital de *Punto Final*

> Revista de izquierda revolucionaria publicada en Chile entre 1965 y 2018.  
> Explora todas sus ediciones digitalizadas, con visor PDF y metadatos abiertos.

<a class="btn btn-primary btn-lg my-3"
   href="{{ '/browse.html' | relative_url }}">
  Explorar la colección
</a>

{% include index/carousel.html title="Documentos Destacados" height="300" %}
{% include index/time.html %}
{% include index/featured-terms.html field="subject" title="Temas Principales" btn-color="primary" %}
{% include index/featured-terms.html field="location" title="Ubicaciones" btn-color="outline-secondary" %}
{% include index/objects.html %}
{% include index/data-download.html %}


