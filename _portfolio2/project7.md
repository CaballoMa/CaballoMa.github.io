---
title: Flocking CUDA Simulation
subtitle: Flocking simulation based on the Reynolds Boids algorithm
image: assets/img/portfolio/fk.png

caption: #what displays in the portfolio grid:
  title: Flocking CUDA Simulation
  subtitle: Flocking simulation based on the Reynolds Boids algorithm
  thumbnail: assets/img/portfolio/fk.png
---

### Intro

In this project, I implemented a flocking simulation based on the Reynolds Boids algorithm, along with two levels of optimization: a uniform grid, and a uniform grid with semi-coherent memory access.

[Github Link](https://github.com/CaballoMa/Project1-CUDA-Flocking)

### Showcase

* 5k boids (naive) 
<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/5k-naive-test.gif" alt="fk">
</p>

* 20k boids (naive)
<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/20k-naive-test.gif" alt="fk">
</p>

* 100k boids (coherent)
<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/100k-coherent-test.gif" alt="fk">
</p>

### Performance Analysis
* Average Frame Rate & Number of Boids (Visualization-On)

<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/VisualizeOnGeneral.png" alt="fk">
</p>

* Average Frame Rate & Number of Boids (Visualization-Off)

<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/VisualizeOffGeneral.png" alt="fk">
</p>

* Average Frame Rate & Block Size (Coherent Grid, 80k boids, visualization-Off)

<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/BlockSize.png" alt="fk">
</p>

* Average Frame Rate & 8 vs 27 Cells (Visualization-Off)

<p align="center">
  <img width="650" height="400" src="../assets/img/portfolio/CellDiffResult.png" alt="fk">
</p>

