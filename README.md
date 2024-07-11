Engineering materials
====

This repository contains engineering materials of a self-driven vehicle's model participating in the WRO Future Engineers competition in the season 2022.

## Content

* `t-photos` contains 2 photos of the team (an official one and one funny photo with all team members)
* `v-photos` contains 6 photos of the vehicle (from every side, from top and bottom)
* `video` contains the video.md file with the link to a video where driving demonstration exists
* `schemes` contains one or several schematic diagrams in form of JPEG, PNG or PDF of the electromechanical components illustrating all the elements (electronic components and motors) used in the vehicle and how they connect to each other.
* `src` contains code of control software for all components which were programmed to participate in the competition
* `models` is for the files for models used by 3D printers, laser cutting machines and CNC machines to produce the vehicle elements. If there is nothing to add to this location, the directory can be removed.
* `other` is for other files which can be used to understand how to prepare the vehicle for the competition. It may include documentation how to connect to a SBC/SBM and upload files there, datasets, hardware specifications, communication protocols descriptions etc. If there is nothing to add to this location, the directory can be removed.

## Introduction

In an era of rapid technological advancements, we introduce the DEElubyo bot, a self-driving robot made entirely of LEGOs, designed to detect and avoid red and green obstacles. This innovative vehicle addresses critical transportation issues, particularly vehicle collisions caused by human error, distraction, and poor visibility. By demonstrating the potential of autonomous systems to enhance safety and decision-making, this project highlights the importance of STEM education and inspires future engineers to tackle transportation challenges, underscoring the role of technology in creating safer roads and a more efficient future.

## Team Details

**Builder:** Dushiel A. Gelido       

**Coder:** Emmanuel Kristoffer O. Jacob

**Researcher:** Enraig G. Gacosta     

## Team Photo

**Official Photo**

**Funny Photo**

## Robot Design

**3D Model**

![3D Model](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/e23e0bc454aefcd58759c99dcca3c8f36269866a/v-photos/3D%20Model.png)  

**Schematic Diagram**

![Schematic Diagram](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/720f28bd67417a89f22368ee3b6f2d5549427a16/schemes/Screenshot%202024-07-08%20141758.png)

**Actual Model**

![actmodel](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/28103a7179e8929c8061afcaf37504025f59bc93/v-photos/Screenshot%202024-07-11%20115741.png) 

## Materials (Components)

**Key Components of the DEElubyo Bot:**   


**Chassis:** 

Holds multiple parts of the robot together, providing a sturdy framework that ensures the structural integrity of the entire vehicle.

![chassis](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/7d73f8a77f737c6af936283065394fe5c97db006/other/Screenshot%202024-07-11%20120700.png)

**Differential (Steering Mechanism):** 

Responsible for turning the front wheels, allowing the robot to steer and navigate through its environment. This mechanism enables the robot to make precise turns and maneuver around obstacles effectively.

![diff](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/e59bf023bb74b19ed1200084c0e6a2508480de1c/other/Screenshot%202024-07-11%20121436.png)

**Servo Motor:** 

Connected to the steering mechanism, it controls its movement. By adjusting the angle of the front wheels, the servo motor allows the robot to change direction as needed.

![servo](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123904.png)

**DC Motor:** 

Drives the rear wheels, providing the necessary power to propel the robot forward. This motor ensures that the robot can move at a consistent speed and handle various terrains.

![dc](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123839.png)

**Wheels:** 

Enable the robot to move. The front wheels are steered by the differential and servo motor, while the rear wheels are driven by the DC motor.

![wheels](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/62c3faea826398e1a21b1945e9774c61b0f557ca/other/Screenshot%202024-07-09%20152316.png)

**Camera:** 

Serves as the robot's eyes, identifying and avoiding obstacles in its path. By processing visual data, the camera helps the robot detect red and green obstacles, enabling it to make informed decisions to avoid collisions.

![camera](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123753.png)

**Microcontroller:** 

Acts as the main brain of the robot, processing data from the camera and other sensors. It makes decisions based on this data and sends commands to the motors and steering mechanism, ensuring smooth and safe operation.

![mcont](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20124029.png)

**Battery:** 

The primary power source for the robot, supplying energy to all its modules. It ensures that the robot has the necessary power to operate its motors, camera, microcontroller, and other components effectively.

![batt](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123947.png)

**Integrated Gray Scale Sensor:**

Identifies colors on the mat, serving as an additional tool for distinguishing between different shades and colors to enhance obstacle detection and navigation.

![ir](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123502.png)

## Code



## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).
