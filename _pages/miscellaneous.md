---
title: "Miscellaneous demos"
permalink: /miscellaneous
---

## 3D CPU Renderer
**Technologies:** C#, WinForms

A built from scratch 3D rendering engine. The whole rendering pipeline is executed on a CPU.

![Preview]({{ site.baseurl }}/assets/img/3d/d1.jpg){:class="img-responsive" : .center-image}

### Features

* Scene editor with 3D shapes, lights and cameras
* Phong interpolation shading
* Point lights with Phong lighting model
* Wireframe rendering with Bresenham line drawing algorithm
* Polygon rendering with scan line polygon filling algorithm
* Triangle back-face culling
* Perspective correction
* Z-buffering for polygon occlusion
* Polygon texture mapping with normal mapping support

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/3d/d2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="3D preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/3d/d3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="3D preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/3d/d4.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="3D preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/2XnvcruwZRA" frameborder="0" allowfullscreen></iframe>

## Soft-body simulation
**Technologies:** C#, WPF, OpenGL

An app with a simple soft-body cube modelled as a set of connected point particles with springs of configurable properties.

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/sb1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Softbody preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/sb2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Softbody preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/sb3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Softbody preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/67H3qU4EvcU" frameborder="0" allowfullscreen></iframe>

## Polygonal lights
**Technologies:** C#, ImGui, OpenGL

A two-person project featuring an implementation of polygonal lights model with linearly transformed cosines (LTC).

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/pls1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Polygonal lights preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/pls2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Polygonal lights preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/pls3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Polygonal lights preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/BQ7Qfc-aVbc" frameborder="0" allowfullscreen></iframe>

## Bullet demo
**Technologies:** C#, Bullet, WPF, OpenGL

A simple simulation using Bullet physics engine with different types of joints.

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/b1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Bullet preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/b2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Bullet preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/b3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Bullet preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/-x3Gl7aDjw0" frameborder="0" allowfullscreen></iframe>


## Rigid-body simulation
**Technologies:** C#, WPF, OpenGL

An accurate simulation of a rigid, spinning cube. The simulation uses 6 DOF Newton equations with Runge-Kutta IV numerical integration.

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/rb1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Rigidbody preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/rb2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Rigidbody preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/rb3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Rigidbody preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/sUL9_-AvJVU" frameborder="0" allowfullscreen></iframe>

## Inverse kinematics
**Technologies:** C#, WPF, OpenGL

A comparison of PUMA robotic arm movement between two types of control: inverse kinematics and linear parameter interpolation. Inverse kinematics method (right) uses quaternion spherical linear interpolation (SLERP) to determine arm's joint angles.

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/ik1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Inverse kinematics preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/ik2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Inverse kinematics preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/ik3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Inverse kinematics preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/0k0IuucSdfI" frameborder="0" allowfullscreen></iframe>

## Polygon clipping & filling
**Technologies:** C#, WinForms

A demonstration of custom implementation of a polygon clipping algorithm and a scan-line polygon filling algorithm. The app also features simple lighting model and texture mapping with normal vector mapping.

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/c1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Clipping preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/c2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Clipping preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/misc/c3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Clipping preview"
     full_width="1280" full_height="720"
  %}
</div>
<br/>
<iframe src="https://www.youtube.com/embed/pEfY4Wh-IMI" frameborder="0" allowfullscreen></iframe>