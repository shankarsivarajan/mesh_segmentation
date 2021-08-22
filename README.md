mesh_segmentation
=================

A simple python addon for blender using spectral clustering to segment meshes. Uses [numpy](http://www.numpy.org/) and [scipy](http://www.scipy.org/) for matrix calculations.
Developed as a project for the spectral-clustering course of University Bremen. Based on the paper "Segmentation of 3D Meshes through Spectral Clustering" by Rong Liu and Hao Zhang (https://doi.org/10.1109/PCCGA.2004.1348360).
### Usage

 - Install [scipy](http://scipy.org/install.html) in the Python installation used by Blender. On Linux, this should be the system Python. On Windows, use [blender_pip](https://github.com/amb/blender_pip).
 - Download "mesh_segmentation.zip" 
 - Install and enable the addon

Now you can select an object in the 3D viewport, hit F3 and search for "Segment Mesh". Clicking on that entry shows the addon in a popup.

<img src="example-results/hand.png" alt="Hand">
You can find more examples in the example-results folder.
