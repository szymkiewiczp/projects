---
title: "CAD & milling simulator"
permalink: /cad
---

A CAD editor with a built-in 3C milling machine simulator and path generator. This project was made for CAD/CAM university courses: *Geometric modeling* and *Design of NC programming systems*

**Technologies:** C#, WPF, OpenGL

![CAD preview]({{ site.baseurl }}/assets/img/cad/c1.jpg){:class="img-responsive" : .center-image}

## Overview
Create parametric curves and surfaces in the editor. Find intersections of objects and create trimmable surfaces. Merge surfaces into a single model. Generate milling machine paths for the model and simulate the milling process. Export the paths to be used in a real-world milling machine.

## Features
* CAD editor
* Variable camera parameters with 3D anaglyph support
* Parametric shapes: toruses, Bezier curves, Bezier surfaces
* Adaptive shape rendering with geometry shaders for smooth shapes
* Gregory patch filling for surfaces
* Curve and surface intersection generation
* Surface trimming with intersection curves
* Milling machine path generation for multi-surface models
* Milling machine simulator for generated paths
* Path export in G-code language

## Gallery

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c7.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1159" full_height="699"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1210" full_height="741"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1245" full_height="779"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c4.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1205" full_height="843"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c5.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1340" full_height="819"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/c1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1466" full_height="904"
  %}
</div>

## [Video](https://www.youtube.com/watch?v=w-WgH9Zyp-8)

<iframe src="https://www.youtube.com/embed/w-WgH9Zyp-8" frameborder="0" allowfullscreen></iframe>

## Real life results

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/r1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1040" full_height="780"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/r2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1040" full_height="780"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/cad/r3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="CAD preview"
     full_width="1040" full_height="780"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/I2TKls6XPRo" frameborder="0" allowfullscreen></iframe>

