---
layout: project
type: project
image: images/topology.JPG
title: Topology Optimization using Finite Element Methods based on Optimality Criteria (Summer of Science)
permalink: projects/topology
date: 2021
labels:
  - Smart Grid
  - Power Quality
  - Play Framework
  - Visualizations
  - Java
  - Grid Map
summary: The project involved Topology Optimization of a Structural and Thermal system using SIMP method in Sigmund-Bendsoe algo. over FEM formulations, achieving an avg. accuracy 92% by validating against standard TopOpt, Ansys app.
---

<img class="ui image" src="{{ site.baseurl }}/images/topology.JPG">

### What is Open Power Quality

The Open Power Quality (OPQ) project is a project aimed at collecting real-time distributed power quality (PQ)
information and performing analytics on the data collected.

### Open Power Quality Hardware

#### OPQBox v1

The original OPQ hardware was developed by our team and samples the raw power waveform at 4000 Hz.
We’re currently able to measure frequency, voltage, and total harmonic distortion with our sensors.
The original OPQ hardware is a combination of a MSP 430 ADC and a Raspberry Pi for onboard number crunching.
The designed and firmware for our hardware is open source and freely available at
 https://github.com/openpowerquality/opq-hardware.

#### OPQBox v2

The new desgin of our OPQ hardware is currently in its final iterations. Please stay tuned for more details.

### Open Power Quality Software (OPQHub)

We designed the OPQ cloud service which aggregates, stores, and performs analytics over the many distributed data points
 from our OPQ devices. The cloud service allows users to view their PQ in real-time while also viewing the PQ around
 them in real-time as well. We use a sophisticated grid-map interface which displays PQ information while maintaining
 our users’ privacy.

We’ve also implemented an open communications protocol to facilitate communication between OPQ hardware devices and the
cloud. All software for this project is freely available and open source and can be found at
 [https://github.com/openpowerquality](https://github.com/openpowerquality)

More information can be found at [http://openpowerquality.org/](http://openpowerquality.org/).
