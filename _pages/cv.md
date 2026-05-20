---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in University of New South Wales, 2026 (Supervisor: Prof. Wei Zhang)
* M.S. in Xidian University, 2021 (Supervisor: Prof. Rui Chen)
* B.S. in Nanjing University of Posts and Telecommunications, 2018

Work experience
======
* 2024.06-09: Fusion Positioning Engineer
  * AutoFlight
  * Duties includes: Lidar point cloud algorithms
  * Supervisor: Qunhe Zhao
  
Skills
======
* PyTorch
* TensorFlow
* C
* C++

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Served as reviewer for IEEE TWC, TMC, TVT, IOTJ, WCL, CL
* TPC for IEEE ICCC 2025
