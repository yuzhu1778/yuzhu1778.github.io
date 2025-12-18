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
  * Self-assembly of janus nanoparticles on lipids membranes 
    * Developed a C++ template to create a model of soft controllable tessellated spherical nanoparticle whcih was integrated with our coarse grained lipid membrane system. Wrote a large number of analysing scripts, using C++, python, and bash, including the Voronoi diagram both in two and three dimensions, radial distribution function, various types of order parameters, Lindemann measure auto-correlation functions, diffusion, free energies, etc.
    * Performed a comprehensive study of the spatial arrangement of two Janus nanoparticles on the outer or inner side  of lipid vesicles by using molecular dynamics method, in conjunction with the calculation of free energy by using weighted histogram analysis method.
    * Performed extensive molecular dynamics simulations to show that highly ordered self-assemblies of NPs can be  mediated by their adhesion to lipid vesicles. Specific geometries of the nanoassemble could be achieved, including  several deltahedra and three Platonic solids, corresponding to the tetrahedron, octahedron, and icosahedron.
    * Performed large scale simulations of Janus nanoparticles adhere to the periodic planar lipid membranes to show  that the nanoparticles self assembly into hexagonal lattice with quasi-long-range order and a hexatic phase at  intermediate densities. I also showed that the melting of nanoparticles from crystal phase to liquid phase agree with KTHNY theory by characterizing Lindemann parameter, bond-order correlation parameter.
    * Performed molecular dynamics simulation of Janus nanoparticles on tubular membranes and showed that the nanoparticles can self-assemble into helical nanoassemblies with variable pitch.
    * Closely collaborated with other students to explore the modes of adhesion of spherocylindrical nanoparticles to tensionless lipid membranes, membrane-mediated dimerization of spherocylindrical  nanoparticles, and the  self-assembly of Janus spherocylindrical nanoparticles on lipid vesicles.
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
  

