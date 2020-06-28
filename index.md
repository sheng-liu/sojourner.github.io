---
layout: page
title:  Sojourner
subtitle: Statistical Analysis of Single Molecule Trajectories
---



> *Sojourner* is a software for statistical analysis of single molecule trajectories. It is implemented in programming language R, with the intend to provide a framework for biophysical metric based statistical analysis of single molecule trajectories. It allows researchers to have a firsthand understanding of their single molecule data with intuitive statistics and visualization.



*Sojourner* is designed primarily for deriving biophysical metrics, such as diffusion coefficient and residence time, from single molecule trajectory data in fast tracking and slow tracking experiments (as in our published paper [ebed pdf here]), and applying statistical analysis on the derived biophysical metrics to have a firsthand intuitive understanding of the data. 

It is mean to provide a framework for single molecule analysis using only simple biophysical metrics and commonly-used statistics to reveal patterns of data for biology researchers; The intended purpose is to serve as an initial run of data for a firsthand intuitive feeling of the raw data with most basic well understood statistics; and may resort to other advanced analysis after. 

For this purpose, it provides simple and easy to understand biophysical metrics, statistical analysis, intuitive graphics, as well as programming techniques for performance enhancement and ease-of-use. 

 

**1. Biophysical metrics**

In the current version (v1.1), we have implemented four biophysical metrics, to benchmark or characterization of degree of diffusion or confinement of molecules without resorting to complex models. The four metrics are: 

1)   Mean Square Displacement for measure types of diffusion; 

2)   Diffusion coefficient to quantify degree of diffusion; 

3)   Residence Time to quantify binding interactions; and 

4)   Packing Coefficient for degree of confinement.

 

**2. Statistical analysis**

Being written in statistical programming language R, it is packed with statistics tools, including well established linear regression or distribution fitting functions, bootstrapping, and other statistical techniques. They are applied in every biophysical metric provided. 

 

**3. Visualization graphics**

All analysis results are represented with intuitive graphics for visualization. Plotting parameters are also output for further customization for publication with other software (e.g. Prism from GraphPad, or …). We have implemented:

1)   Various ways for visualizing trajectories, including plotting indexed individual or masked clustered trajectories over original image, color coded with a biophysical metrics or statistics.

2)   Curated density or histogram plots for displaying distributions and highlight its differences between datasets. 

 

**4. Programming techniques for performance and ease-of-use**

We have applied performance enhancement strategies and graphical interface solutions available in R for a better use experience. This include, 

1)   Parallel computation using parallel [ ] package and C implementation of the time restricting functions using Rcpp [ ] package to enhance the performance of the code. 

2)   For ease-of-use purpose, we have implemented a graphical user interface (GUI) for most frequently used functions using Shinny package. It can be independently hosted as sever or launch from an R console for people who doesn’t usually use command line. 

3)   We also have implemented supports for multiple trackers for convenience. It currently include Diatrack [ ], ImageJ plugin Particle Tracker[ ] and TrackMate[ ], MatLab based SLIMfast[ ] and u-track[ ].  Further supports can be easily added because of simple data structure we used. 

 

> *Sojourner* is an Open Source project. It is written by and for biology researchers, and bares simplicity in mind. It is about Simple Analysis Done Thorough. 







