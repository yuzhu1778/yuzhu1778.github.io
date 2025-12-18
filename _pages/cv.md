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
* M.S. in computer science, Georgia Institute of Technology, 2025
* Ph.D in Applied physics, University of Memphis, 2023
* M.S. in Computational phyiscs, University of Memphis, 2020
* B.S. in Physics, University of Memphis, 2018
* B.S. in Physics, Anhui University, 2018
Work experience
======
* ==August 2019-July 2024: Position: Research Assistant==
  *   Self-assembly of janus nanoparticles on lipids membranes 
    Developed a C++ template to create a model of soft, controllable tessellated spherical nanoparticle, whcih was
integrated with our coarse grained lipid membrane system. Wrote a large number of analysing scripts, using C++,
python, and bash, including the Voronoi diagram both in two and three dimensions, radial distribution function,
various types of order parameters, Lindemann measure, auto-correlation functions, diffusion, free energies, etc.

  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * GitHub University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * GitHub University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

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
  

