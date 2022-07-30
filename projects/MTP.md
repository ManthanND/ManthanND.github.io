---
layout: project
type: project
image: images/MTP.PNG
title: Development of a Multi-Physics FEM model with Voxel based porosity algorithm for defect prediction in LPDC components
permalink: projects/MTP
date: 2022
labels:
  - Finite Elements
  - Computational Fluid Dynamics
  - Multiphysics
  - Simulations
summary: The project involves development of a Multi-Physics FEM model of Low Pressure Die cast Aluminium alloy wheel for shrinkage porosity reducion using voxel based post processing algorithms.
---

<img class="ui image" src="{{ site.baseurl }}/images/MTP.PNG">

### Abstract

The automobile wheel market is expected to grow by almost 5.52% from 5 years now. Majority of 
the market of the automobile wheels is occupied by Aluminium alloys because of numerous 
advantages, one of which includes light weight. The most preferred manufacturing process for the 
Aluminium alloy wheels is the Low Pressure Die Casting. However, the process is accompanied 
by various defects, some of which reflect significantly on the fatigue and impact properties are 
Shrinkage, gas porosity, oxide film and oxide inclusions. The severity of the defects not only 
depends upon the type or quantity, but also on the location of the defect. Some of the visible defects 
can be reworked, few of which that do not pass the quality conformance are re-melted. It would 
be much economical to design the mold, cavity, die cooling circuit and appropriately set the 
process parameters, which will reduce the defects and its severity. Various physics that are 
involved in LPDC process are Heat Transfer, Free-Surface and Turbulent flow, Phase 
transformation and Alloy composition. A Multi-physics simulation can incorporate all the 
mentioned physics required for LPDC. Various input set-point parameters that can contribute in 
Shrinkage porosity are Mold pre-heat temperatures, Pressure Cycle, Cooling channel flow-rates, 
delay and duration. The FEM-FVM simulation tools provide an FEM output like phase fractions, 
from which shrinkage porosity is calculated via post-processing techniques. On the other hand 
industrial softwares apply some simplified or approximate solutions to calculate porosity, which 
may not always be true. A better approach here would be to use FEM-FVM tool to calculate phase 
fractions, and then apply a post-processing algorithm based on the shrinkage physics to track the 
porosity quantity and location. Once a simulation data with porosity results are obtained, a 
Machine Learning algorithm can help provide predictive and prescriptive analytics. An 
optimization algorithm can also be developed based on the simulation results to suggest a recipe
(input set-point parameters) for minimizing shrinkage porosity. The current thesis focuses on 
developing a Multi-physics model for LPDC of automobile wheel, followed by post-processing 
voxelization and density based algorithms to locate and quantify shrinkage porosity. It also 
discusses a Multi-Disciplinary design optimization approach for suggesting a recipe for minimal 
defects in the wheel. A machine learning approach is also discussed to predict and prescribe the 
wheel quality.


