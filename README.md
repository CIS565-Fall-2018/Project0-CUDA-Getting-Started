Project 0 CUDA Getting Started
====================

**University of Pennsylvania, CIS 565: GPU Programming and Architecture, Project 0**

* Ziad Ben Hadj-Alouane
  * [LinkedIn](https://www.linkedin.com/in/ziadbha/), [personal website](https://www.seas.upenn.edu/~ziadb/)
* Tested on: Windows 10, i7-8750H @ 2.20GHz, 16GB, GTX 1060

### Building & Running

Building & Running the app were done as per the instructions. I used Visual Studio 2015 to run build and ran both the Release and Debug versions. The output was the same in both cases as highlighted below.

## App Window
<p align="center">
  <img src="https://github.com/ziedbha/Project0-CUDA-Getting-Started/blob/master/images/app.png"/>
</p>

### Profiling

Through NSight, I obtained the following timeline trace:

## Timeline
<p align="center">
  <img src="https://github.com/ziedbha/Project0-CUDA-Getting-Started/blob/master/images/timeline1.png"/>
</p>

### CUDA Debugging

I initially ran into a "grid launch failure" error when I tried to run the CUDA debugger. It turns out that my NSight version was too low. Updating it to 5.6 fixed the issue. I was able to place breakpoints, edit their hit conditions, and examine autos. I was also able to examine information about kernels, blocks, and warps through the CUDA Info NSight menu.

## Autos
<p align="center">
  <img src="https://github.com/ziedbha/Project0-CUDA-Getting-Started/blob/master/images/autos.png"/>
</p>

## CUDA Info (Warps)
<p align="center">
  <img src="https://github.com/ziedbha/Project0-CUDA-Getting-Started/blob/master/images/warps.png"/>
</p>
