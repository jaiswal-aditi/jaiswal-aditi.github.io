---
layout: project
type: project
image: images/project1.png
title: Parallel Implementation of Gray Level Co-occurrence Matrix Construction using MPI
permalink: projects/parallelharalick
# All dates must be YYYY-MM-DD format!
date: 2021-12-12
labels:
  - C
  - MPI
  - Image Classification
  - Computer Vision
summary: This work presents two algorithms, using MPI, for parallel computation of gray-level co-occurence matrices, a precursory step to computation of the Haralick texture features.
---

<img class="ui medium right floated rounded image" src="../images/project1.png">

Image texture is an important feature in computer vision tasks. Textural features have been developed to allow for objective comparison of textures between images and image regions. [Haralick](https://ieeexplore.ieee.org/document/4309314) introduced the Gray-Level Co-Occurrence Matrix (GLCM) in 1973 as a necessary step for the computation of the Haralick texture features. The GLCM is a flexible measure of spatial dependence between pixel gray levels which is defined by an angle, a distance, and the unique gray tones in an image. But algorithms extracting Haralick features an dGLCM are computationally intensive, which is why there is a need for parallelization for this task.

MPI is one such technique to achieve parallelism. It is a standard "message passing interface" designed for distributed memory systems, providing routines for both blocking, non-blocking and collective communication between processes. `MPI_Send` represents a blocking send procedure.  A single envelope of data is sent from  process 'x' to process 'y'. The program cannot continue until process 'y' acknowledges receipt of the envelope. `MPI_Recv` represents a blocking receive procedure.  After process 'x' sends its envelope, process 'y' must wait until it receives the envelope from process 'x' to proceed. We used MPI to partition out the image too.  Each process independently constructs a section of the GLCM. A single rootprocess then gathers the partial GLCMs, computed by the processes, and combines them into a single GLCM for the image.

In this project we implemented two different parallel implementations of the GLCM construction process in C using MPI: row-based and tiled. The row-based parallel algorithm computes the GLCM for a particular combination of a grayscale image `A`, an angle `a`, a distance `d` and number of processes `X`. The tiled parallel algorithm computes the GLCM for a particular combination of a grayscale image `A`, an angle `a`, a distance `d` and a number of processes `X`. Each algorithm makes use of MPI processes having their own memory to store partial computations and a copy of the grayscale image, while referring to a relevant section of the grayscale image. The grayscale image is stored as a flat array of size `N×M` to speed up indexing operations. We evaluated the execution times of a sequential, row-based and tiled algorithm in a simulated environment and on the [MANA](https://datascience.hawaii.edu/hpc/) cluster.  We found that is a reasonable approach for reducing execution time for large images and achieved a speedup ratio > 2 for 1600×1600 images.

Source: <a href="https://github.com/jaiswal-aditi/parallel-haralick"><i class="large github icon"></i>jaiswal-aditi/parallel-haralick</a>


