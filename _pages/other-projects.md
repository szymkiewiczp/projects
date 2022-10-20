---
title: "Other projects"
permalink: /other-projects
---

## Skype chat log manager

**Technologies:** C#, WinForms

A comprehensive utility tool for Skype chat history management. Import your local Skype 7 database and incrementally add new message logs from Skype 8's export page. The logs can be exported to a human-readable form based on the original Skype 7 message format. The tool also parses any custom message types (RichText, quotes etc) to display them properly. The program is bundled with other utility tools to help you extract certain data from your logs.

### Background

Back when Skype version 7 existed you could access your whole locally-saved chat history from the app. When Microsoft removed Skype 7 in favor of version 8 back in 2019, the chat history was moved entirely to the cloud. It was said that the chat history would only contain messages from the last 2 years and there would be no local chat storage except for the official export page. This tool was developed in order to merge old local chat database with new incremental cloud backups.

### Features

* Merge Skype 7 and Skype 8 logs together
* Keep an incremental local backup of your whole chat history
* Save your chat history to a readable text file
* Add custom display names for other users
* Extract internal message schema from over 30 message types
* Log analysis
	* User statistics
	* Conversation statistics
	* Message content statistics

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/skype1.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Skype manager preview"
     full_width="2600" full_height="1080"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/skype2.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Skype manager preview"
     full_width="1916" full_height="969"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/skype3.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="300" alt="Skype manager preview"
     full_width="1845" full_height="884"
  %}
</div>

## Video clipper

**Technologies:** C#, WPF, FFmpeg

Extract short clips from your videos - select start and end time, preview the clip and save it. A great tool to extract smaller pieces from your gameplay videos or movies. Your clipping history is saved in case you want to track your editing progress when working with longer videos.

### Features

* Simple clip creation from local videos
* Clip history for progress tracking
* Asynchronous rendering
* Random clip suggestions

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/video1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Clipper preview"
     full_width="1280" full_height="720"
  %}
</div>

## Backup tool

**Technologies:** C#, WinForms

If you manage your file backups manually, you want to make sure you don't make any mistakes while backing up your data. If you have many copies of your files on different drives, this tool can help you with making sure that no file has been left. It also helps you with finding the files you might want to be interested in backing up. This software is meant to help you with your data backup management if you want to have full control of what is being saved on your backup drives. This tool is tailored for specific use cases when there are multiple drives with common files (for example on different machines or backup media).

### Features

* Create and save snapshots of your file structure
* Compare snapshots to find missing or updates files
* See which files and directories take up the most space
* Detect file system issues
* Reduce your backup size by finding duplicate files

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/backup1.jpg
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Backup preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/backup2.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="350" alt="Backup preview"
     full_width="1218" full_height="879"
  %}
</div>

## Minecraft utility plugin
**Technologies:** Java, Spigot API

A plugin for Minecraft servers with Spigot API. The tool aggregates over 80 utility commands to help server administrators with server management and debugging. It also provides entertainment commands for players.

### Features

* World-editing tools
* Ticket tracking
* Performance monitoring
* Command templates and chaining
* Moderator tools
* Player utilities

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/util1.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Utility preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/util2.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Utility preview"
     full_width="1280" full_height="720"
  %}
</div>

## Minecraft game log extractor
**Technologies:** C#

A utility tool to aggregate Minecraft client and server logs into easy-to-read text files. Minecraft logs contain useful information like chat history or server errors. Every time you launch a client or a server, the logs are put into a new file. This tool helps you with log management by aggregating log files into a single text file. You can filter certain types of messages to create full chat history, command usage or error list. The tool supports both new (date.log.gz) and old (server.log) formats.

### Features

* Merge multiple Minecraft log files into one
* Supports client logs, vanilla servers and Spigot servers
* Create unified per-server log files
* Filter out unwanted message types
* Fix chat color code formatting in game logs
* Strip chat thread info from chat messages
* Automatically convert server encodings into UTF-8

### Output format example

<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/mclog.png
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Log preview"
     full_width="1050" full_height="899"
  %}
</div>

## Other games
<div class="photoswipe-gallery">
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/diamonds.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Diamonds preview"
     full_width="1280" full_height="720"
  %}
   {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/flappy.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Flappy preview"
     full_width="1280" full_height="720"
  %} 
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/reds.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Reds preview"
     full_width="1280" full_height="720"
  %}
  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/bricks.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Bricks preview"
     full_width="1280" full_height="720"
  %}


  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/hero.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="450" alt="Hero preview"
     full_width="1280" full_height="720"
  %}

  {% capture image_path %}
  {{ site.baseurl }}/assets/img/projects/2048.gif
  {% endcapture %}
  {% include image.html 
     url=image_path
     thumb_width="240" alt="2048 preview"
     full_width="792" full_height="840"
  %}
</div>