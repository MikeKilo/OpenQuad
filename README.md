# OpenQuad
## Open Source Quadcopter Frame ##
![alt tag](https://github.com/MikeKilo/OpenQuad/blob/master/MK210.40.jpg)
## Summary ##
Hello All!

Quadcopters are amazing machines - both for fun and as an engineering education tools. 
While the software part is very well covered in open source projects (APM, Cleanflight / Betaflight...), the hardware part remains neglected. This GIT aims to change that!

To begin with, the project will focus on quadcopter mechanics - the frame itself, 3d printed parts and so on, but hopefully, in the future, electronics hardware will follow. 

I am starting this project with a ~210 race frame, single part base style, but I would love to see more designs branching from this one, or totally new projects running along.

Best scenario for this project, on my part, is visiting this site few months from now and seeing that the design took a completely new direction and that I won't recognize the frame we started with.

Have fun building and crashing!

## Project Goals ##
This project has several goals:

1. Iterative improvement of quadcopter hardware using community insights, experience (wisdom of the crowd, as they say...) and *Time* :smile:
2. Encouraging standardization of electronics - as was the case with the ubiquitous 35x35 footprint for boards with 30x30 mounting holes, the more popular and common frame designs will get, the more standard form factor equipment will appear.
3. Experimenting with hardware open source and source control tools - the age of additive manufacturing and homemade CNC is already here, the tools should follow suite.
3. Have fun!

## Frame Design Principles ##

![alt tag](https://github.com/MikeKilo/OpenQuad/blob/master/Frame dimensions V3.png)
![alt tag](https://github.com/MikeKilo/OpenQuad/blob/master/MK210.46.jpg)

## Configuration Management of 3D Parts and the Data Repository ##
GitHub [supports 3D files configuration management](https://help.github.com/articles/3d-file-viewer/), but only for .STL extensions. while not the best format for full assemblies and parts to be manufactured in CNC, it is very suitable for 3D printed parts.
For our purpose, it can be used as a visual way to track changes and modificatins done by the community, for example:
![alt tag](https://github.com/MikeKilo/OpenQuad/blob/master/GitHub_STL_Diff.jpg)
All manufacturable files shall be uploded in Solidworks 2014 format, while STL files will be used in order to track changes. 
