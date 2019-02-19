---
layout: project
type: project
image: images/argon_sim.png
title: Liquid Argon Simulation
permalink: projects/liquid_argon
# All dates must be YYYY-MM-DD format!
date: 2018-10-21
labels:
  - Javascript
  - Threejs
  - Fortran
summary: A 3D visualization of a liquid argon simulation
---

  <img class="ui large image" src="../images/liquid argon.gif">
  
In CHEM 761 we were assigned a project to produce a simulation of liquid argon. This was a especially difficult project for me as theory and programming had to be combined together to achieve the result. Without the help of Kazuumi Fujioka I may have not been able to produce this. 

Initially the fortran simulation utilized 3 dimensional arrays to record positions of argon atoms over time. The positions of atoms over time were then written to a text file and loaded onto a program called VMD for visualizaiton. Using threejs I then made the visualization browser based, instead of only being viewable in VMD or gif format. 
  
 
[Link to Simulation](https://akkamin.github.io/threejs_example/example/examples/argon_simulation/argon_simulation.html)

[Link to github repository](https://github.com/akkamin/threejs_example)


