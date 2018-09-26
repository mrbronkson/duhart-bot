# Duhart bot

## 2 DOF robot arm control by object tracking

This is a project I developed a time ago for a robot vision class, where a 2 DOF arm can be controlled by tracking the position of an object.

The program naively learns the color of the object you wish to track trough an histogram and then converts the pixel coordinates of the object to workspace coordinates. Finally, workspace coordinates are translated into robot angles by inverse kinematics.

The program shows an overlay of the robot, while it can also be used to manipulate a physical robot I built with a Bioloid Premium kit.

I wrote the initial code for Visual Studio 2010 with OpenCV 2.4.9.0. This repo has the source code for the program (including communication program Send.exe), the files for the robot (CM530/) and a working executable tested in Windows 10 (Debug/ProyectoVision.exe).

I will work to improve this project in the future.
