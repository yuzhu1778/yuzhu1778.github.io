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
* **Position: Postdoctoral Associate  at Purude University, August 2023-present**
  * **Project:** Multi-scale modeling of lipid nanoparticles and proteins
    * Developed a progressive coarse-graining framework for mapping all-atom protein models to highly coarse-grained representations using essential dynamics and fixed-length methods.
    * Designed a neural-network-based backmapping method to recover all-atom protein structures from coarse-grained models.
    * Developed tools to construct and parameterize lipid nanoparticles based on all-atom simulations.
* **Position: Research Assistant at University of Memphis, August 2019-July 2023**
  * **Project:** Self-assembly of janus nanoparticles on lipids membranes 
    * Developed a C++ template to create a model of soft controllable tessellated spherical nanoparticle whcih was integrated with our coarse grained lipid membrane system. Wrote a large number of analysing scripts, using C++, python, and bash, including the Voronoi diagram both in two and three dimensions, radial distribution function, various types of order parameters, Lindemann measure auto-correlation functions, diffusion, free energies, etc.
    * Performed a comprehensive study of the spatial arrangement of two Janus nanoparticles on the outer or inner side  of lipid vesicles by using molecular dynamics method, in conjunction with the calculation of free energy by using weighted histogram analysis method.
    * Performed extensive molecular dynamics simulations to show that highly ordered self-assemblies of NPs can be  mediated by their adhesion to lipid vesicles. Specific geometries of the nanoassemble could be achieved, including  several deltahedra and three Platonic solids, corresponding to the tetrahedron, octahedron, and icosahedron.
    * Performed large scale simulations of Janus nanoparticles adhere to the periodic planar lipid membranes to show  that the nanoparticles self assembly into hexagonal lattice with quasi-long-range order and a hexatic phase at  intermediate densities. I also showed that the melting of nanoparticles from crystal phase to liquid phase agree with KTHNY theory by characterizing Lindemann parameter, bond-order correlation parameter.
    * Performed molecular dynamics simulation of Janus nanoparticles on tubular membranes and showed that the nanoparticles can self-assemble into helical nanoassemblies with variable pitch.
    * Closely collaborated with other students to explore the modes of adhesion of spherocylindrical nanoparticles to tensionless lipid membranes, membrane-mediated dimerization of spherocylindrical  nanoparticles, and the  self-assembly of Janus spherocylindrical nanoparticles on lipid vesicles.
  * **Project:** Ring polymers as a model for cellular organization 
    * Developed a Metropolis Monte Carlo code and an effcient molecular dynamics software with C++, and OpenMP  for the study of the conformational behavior of disjoint ring polymers as a function of their areal density, and  degree of flexibility on the substrate.
    * Based on the model of ring polymers, developed analysis tools to explore the collective motion of self-propelled  particles(cells), and the vorticity Reversals of self-propelled particles (cells) on Circularly Patterned Substrates.

Skills
======
* **Languages and Tools:**
  * C/C++, Python, bash script, SQL, GROMACS, Amber, PyMOL, MDAnalysis, TensorFlow, PyTorch, Git, Vim, slurm, VMD, xmgrace, Latex
* **Related Courses:**
  * Probability/Statistics, Differential Equations, Machine Learning for Trading, Computer Networks, Software Dev Process, Machine Learning, SQL for Data Science, Mechanical Behavior Of Materials, Quantum  Mechanics, Soft Matter/Biological Physics, Polymer Physics, Algorithms/Problem Solving, Methods/Computational Physics Statistical Mechanics, Electrodynamics, Materials Physics
* **Miscellaneous Technologies:**
  * Time series analysis, High-Performance Computing, Monte Carlo, Molecular dynamics, data visualization, mathematical modeling, Random forests, Reinforcement learning, lipid membranes, polymers,  self-assembly, collective behavior, free energy calculations, multi-scale modeling, nanomedicine desigin

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
* **August 2018-August 2020: Position: Teaching Assistant**
  * Taught undergraduate level Physics Lab(I−III), set up experiments, Proctored tests, and graded coursework.


