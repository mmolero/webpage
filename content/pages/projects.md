Title: Projects


## <img src="../images/logo-SimNDT.png" width="40", height="40"> SimNDT  

Software simulator written in Python with the following features:

Parallel implementation of Viscoelastic EFIT (Elastodynamic Finite Integration Technique): 

- 2D P/SV: 2th spatial-time order (Elastic/Viscoelastic Media)
- Parallel codes using OpenCL via PyOpenCL
- Capable to simulate Ultrasonic NDT inspection systems: Pulse-echo, Through-Transmission, Linear Scan, Radial Scan, Tomography 
- Capable to generate various type of geometric scenarios
- Capable to export simulation results in .Mat-File Format

![](../images/SimNDT.gif)


if you are interesting in collaborating and/or testing this software, please don't hesitate to contact me

Please check the first [pre-release](https://github.com/mmolero/SimNDT/releases)


## pcloudpy <img src="../images/pcloudpy.png" width="60", height="60">

Point Cloud Viewer and Processing Toolkit in Python


This toolkit aims at providing an ease interface to display point clouds in many formats and performing diverse filtering processes. 
This project goal is to make use of amazing libraries such as numpy, scipy, matplotlib, IPython, VTK, pandas, sklearn, laspy, pyside, pyqode and so on to be used in the display and processing of point clouds.
**pcloudpy** project is highly inspired in Paraview, MeshLab, CloudCompare, FreeCad, PCL.  It attempts to offer an alternative to add modules written in python easily. 
An IPython Console and a Python Editor are also available in order to interact with the pcloudpy api and graphical user interface.


The main features of the pcloudpy module are the following:

- Display dense point clouds
- Selection and Cleaning of point clouds
- Filtering of point clouds
- Delaunay Triangulations
- Interaction with pcloudpy modules from an embedded IPython Console

<img src="../images/pcloudpy_v0.10.png" width="800", height="500">
