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

## Materials (Components)

**Key Components of the DEElubyo Bot:**

**Chassis:** 

Holds multiple parts of the robot together, providing a sturdy framework that ensures the structural integrity of the entire vehicle.

**Differential (Steering Mechanism):** 

Responsible for turning the front wheels, allowing the robot to steer and navigate through its environment. This mechanism enables the robot to make precise turns and maneuver around obstacles effectively.

**Servo Motor:** 

Connected to the steering mechanism, it controls its movement. By adjusting the angle of the front wheels, the servo motor allows the robot to change direction as needed.

**DC Motor:** 

Drives the rear wheels, providing the necessary power to propel the robot forward. This motor ensures that the robot can move at a consistent speed and handle various terrains.

**Wheels:** 

Enable the robot to move. The front wheels are steered by the differential and servo motor, while the rear wheels are driven by the DC motor.

**Camera:** 

Serves as the robot's eyes, identifying and avoiding obstacles in its path. By processing visual data, the camera helps the robot detect red and green obstacles, enabling it to make informed decisions to avoid collisions.

**Microcontroller:** 

Acts as the main brain of the robot, processing data from the camera and other sensors. It makes decisions based on this data and sends commands to the motors and steering mechanism, ensuring smooth and safe operation.

**Battery:** 

The primary power source for the robot, supplying energy to all its modules. It ensures that the robot has the necessary power to operate its motors, camera, microcontroller, and other components effectively.

## Code



## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).
