---
title: "Gravitational Simulator for performance-oriented programming in C++" 
excerpt: "The objective of this project is to analyze and compare the performance of the aos and soa structures in the context of a gravitational simulator implemented in C++. <br/><img src='/images/project-Gravitational/output_frames.gif'>"
collection: portfolio
---
<p align="center">
  <img width="70%" src='/images/project-Gravitational/output_frames.gif'>
</p>
The objective of this project is to analyze and compare the performance of the aos and soa structures in the context of a gravitational simulator implemented in C++. The primary difference between these structures lies in the way objects are stored. aos uses an array of structures, while soa adopts a structure of arrays approach. By comparing their performance, we can gain insights into the efficiency and effectiveness of each structure type in the gravitational simulation scenario.

Furthermore, we explore the potential performance improvements achieved by parallelizing the code using OpenMP. Parallelization enables the execution of code across multiple threads, harnessing the power of modern processors and potentially enhancing overall performance.

This project was developed as part of the Computer Architecture subject in the Computer Engineering degree program at UC3M.