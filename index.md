---
layout: default
title: Archivo Punto Final
---
<img src="assets/img/fondo-punto-final.jpg" alt="Portada Punto Final" style="width:100%; max-height:600px; object-fit:cover;">

<div class="row">

  <div class="col-md-8">
    {% include index/description.html %}
    {% include index/carousel.html title="Sample Items" height="300" %}
  </div>

  <div class="col-md-4">  
    {% include index/time.html %}
    {% include index/featured-terms.html field="subject" title="Top Subjects" btn-color="primary" %}
    {% include index/featured-terms.html field="location" title="Locations" btn-color="outline-secondary" %}
    {% include index/objects.html %}
  </div>

  <div class="col-md-12">
    {% include index/data-download.html %}
  </div>

</div>
