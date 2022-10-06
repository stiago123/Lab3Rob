<h1 align="center"; style="text-align:center;">Laboratory 3: Industrial Robotics Inputs and Outputs</h1>
<p align="center";style="font-size:50px; text-align:center; line-height : 50px;  margin-top : 0; margin-bottom : 0; "> <br> Universidad Nacional de Colombia</p>
<p align="center";style="font-size:50px; text-align:center; line-height : 50px;  margin-top : 0; margin-bottom : 0; "> <br> Robotics</p>
<p align="center";style="font-size:50px; text-align:center; line-height : 40px;  margin-top : 0; margin-bottom : 0; "> <br> Santiago Mariño (samrinoj) - Daniel Pineda (dpinedasi)</p>


<p align="center"; style="font-size:50px; text-align:center; line-height : 30px; margin-top : 0; "> <br>October 7  2022</p>

## Introduction

This lab aims to implement and use the digital input and output module of the IRC5 controller through RAPID code in RoboStudio.

The idea is to be able to select the desired pose for the 1RB140 Robot through a digital input and know its status through a digital output. 

## Solution Description

- With the help of the RobotStudio software, targets, paths are created for each relaxed pose and writing routine. The desired positions are:
    * Home Position (All angles equal to 0) 
    * Position for the tool mount
    * Writing routine of SM-DP letters
- The RobotStudio controller is created with 3 digital inputs and 1 digital output. The controller is restarted and we can use these inputs and outputs in the I/O simulator
- Finally, each routine and position is assigned the digital input as action
- In the simulation it is verified that actions only happen after activating the digital input 

## Demonstration video
### RobotStudio Simulation
[![Simualcion](http://img.youtube.com/vi/6UFMKc55c4w/0.jpg)](https://www.youtube.com/watch?v=6UFMKc55c4w&ab_channel=DanielPineda)

### LabSir Implementation
[![Simualcion](http://img.youtube.com/vi/ubIaZkqMFJU/0.jpg)](https://www.youtube.com/watch?v=ubIaZkqMFJU&ab_channel=DanielPineda)

## Code in RAPID

- The configuration and programming of the robot can be exported from a RAPID code which will be loaded later to the physical controller of the robot, this code is found in \Lab3SMDP-IO-RAPID










	



