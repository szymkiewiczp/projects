---
title: "Minecraft minigame engine"
permalink: /minecraft-game-engine
---

A plugin for Minecraft Java Edition servers with Spigot API. The engine simplifies the process of creating and managing your games created for multiplayer servers. In 2022 the core of this game engine was rewritten from scratch for a master's thesis in computer science: *Game engine for Minecraft Java Edition servers with Spigot API*.

**Technologies:** Java, Spigot API

![Preview]({{ site.baseurl }}/assets/img/engine/s1.jpg){:class="img-responsive" : .center-image}

## Overview
This game engine simplifies the process of developing games for Minecraft servers. It creates a layer between games and Minecraft servers. The engine is reponsile for resource management, game isolation and handling of default game events. It speeds up the process of game logic implementation, custom game item development and bidirectional communication with players.

Engine users create their games in Java as standard Spigot plugins, which reference the engine's API. On top of the general object-oriented approach, several engine subsystems, such as game logic management system, take advantage of an Entity Component System (ECS), where server game developers create their own components that extend the base functionality of games and game rooms.

## Features
* **Game management** - the core of the engine responsible for handling game logic, maps and players
* **Custom command interface** - simplifies the process of creating and managing player chat commands as a user interface
* **Data storage** - resource management system responsible for storing game data in the file system
* **Item management system** - allows easy custom game item development and management
* **Damage system** - responsible for custom damage tracking for battle games
* **Entity management** - entity tracking system for easier game object manipulation
* **Graphical user interface** - simplifies the process of creating and managing custom graphical interface
* **Destructible environment** - terrain system for geometry modification and structure collapsing
* **Utility tools** - smaller components and algorithms for easier game development
	* Particle system
	* Explosion system
	* Sound system
	* Geometry algorithms and data structures
	* Many more...

## Gallery

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s2.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s3.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
    {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s4.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s5.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s6.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
    {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s7.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s8.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
    {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s10.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s11.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s12.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/s14.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  

  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g2.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g4.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g5.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g1.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
   {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g3.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
   {% capture image_path %}
  {{ site.baseurl }}/assets/img/engine/g6.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Game engine preview"
     full_width="1280" full_height="720"
  %}
</div>

## [Gameplay Clips](https://www.youtube.com/watch?v=_JM-uf86f5I)

<iframe src="https://www.youtube.com/embed/_JM-uf86f5I" frameborder="0" allowfullscreen></iframe>

## [Deathmatch Gameplay](https://www.youtube.com/watch?v=gf2G4lyi8X4)

<iframe src="https://www.youtube.com/embed/gf2G4lyi8X4" frameborder="0" allowfullscreen></iframe>

## [Dogfight Gameplay](https://www.youtube.com/watch?v=dK7UXT14nTA)

<iframe src="https://www.youtube.com/embed/dK7UXT14nTA" frameborder="0" allowfullscreen></iframe>