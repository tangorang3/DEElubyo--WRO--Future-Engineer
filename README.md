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

The DEElubyo bot, a self-driving robot that's both innovative and fun. Built with LEGO bricks for its body, powered by Arduino modules for its brain, and equipped with an AIsteam of motors, batteries, and sensors, this little robot is designed to detect and avoid red and green obstacles. The DEElubyo bot is a perfect blend of playfulness and advanced technology, showcasing how we can use creative building materials alongside serious electronics to tackle real-world problems like reducing car accidents and making our roads safer. This project isn't just about tech; it's about inspiring the next generation of engineers and technologists by combining creativity, engineering, and innovation. With the DEElubyo bot, we see how integrating different components can lead to smart solutions and highlight the importance of STEM education in shaping a better future.

## Team Details

**Builder:** Dushiel A. Gelido       

**Coder:** Emmanuel Kristoffer O. Jacob

**Researcher:** Enraig G. Gacosta     

## Team Photo

**Official Photo**

**Funny Photo**

## Step by Step Process

![spsdiag](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b794dfe25aa2774d3cc1d589902f617d293e0e2/other/IMG_0966.jpeg)

## Robot Design 

*3D Model (Draft)*

![ajf](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/3ea03cc6520a0cb84045d0c354e12f3673abb9d8/other/Screenshot%202024-08-20%20000129.png)

*Schematic Plan (Draft)*

![Schematic Diagram](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/720f28bd67417a89f22368ee3b6f2d5549427a16/schemes/Screenshot%202024-07-08%20141758.png)


---------------- 

*3D Model (Final Output)*

![ajsf](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/ae5ead9214f8a6f5d876b02b4008bf6ac3220c3b/other/455143741_1205153603942597_8343573259965419887_n%20(1).jpg)

*Schematic Plan (Final Output)*

![asfa](


*Official Robot (Final Output)*



## Materials (Components)

***Key Components of the DEElubyo Bot:***

**LEGO Chassis:**

Holds multiple parts of the robot together, providing a sturdy framework that ensures the structural integrity of the entire vehicle.

![chassis](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/c8753ab1ab76a8597c9ccb03adc03313dec53ddf/other/IMG_0969.jpeg)

**Differential (Steering Mechanism):** 

Responsible for turning the front wheels, allowing the robot to steer and navigate through its environment. This mechanism enables the robot to make precise turns and maneuver around obstacles effectively.

![diff](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/9ece7a98e5d3ef7b1cd5ed35460dd66aad6e7de3/other/IMG_0971.jpeg)

**5V Simulated Steering Module:** 

Connected to the steering mechanism, it controls its movement. By adjusting the angle of the front wheels, the servo motor allows the robot to change direction as needed.

![servo](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123904.png)

**7.4V Ordinary Motor Module:** 

Drives the rear wheels, providing the necessary power to propel the robot forward. This motor ensures that the robot can move at a consistent speed and handle various terrains.

![dc](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123839.png)

**Wheels:** 

Enable the robot to move. The front wheels are steered by the differential and servo motor, while the rear wheels are driven by the DC motor.

![wheels](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/62c3faea826398e1a21b1945e9774c61b0f557ca/other/Screenshot%202024-07-09%20152316.png)

**SEN0305-S Husky Lens :** 

Serves as the robot's eyes, identifying and avoiding obstacles in its path. By processing visual data, the camera helps the robot detect red and green obstacles, enabling it to make informed decisions to avoid collisions.

![camera](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/53d769406da8ff102def24d6fcc7b31851dffc8a/other/Screenshot%202024-07-22%20180644.png)

**Arduino Uno R3:** 

Acts as the main brain of the robot, processing data from the camera and other sensors. It makes decisions based on this data and sends commands to the motors and steering mechanism, ensuring smooth and safe operation.

![mcont](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/3d124c402bb7801d6a01589d2ee9242fafec0900/other/Screenshot%202024-07-22%20181202.png)

**Lithium Battery Module:** 

The primary power source for the robot, supplying energy to all its modules. It ensures that the robot has the necessary power to operate its motors, camera, microcontroller, and other components effectively.

![batt](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6b5172c78027737333dd0192c2d5283dd9a0bc72/other/Screenshot%202024-07-09%20123947.png)

**DC to DC LM2596S Buck Converter**

DC-DC buck converter is crucial in Arduino projects to efficiently reduce higher input voltages from sources like batteries or power supplies to the lower, stable voltages (e.g., 5V or 3.3V) required by Arduino boards. This regulation prevents potential damage, optimizes power efficiency by minimizing heat generation, and ensures reliable operation, especially in battery-powered applications where extending operational time is essential.

![buck converter](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6a3b6f0b85c2e4f342909a756c382c16b59c9f45/other/Screenshot%202024-07-22%20183241.png)

**HC-SR04 Ultrasonic Sensor**

The HC-SR04 Ultrasonic Sensor is used as an obstacle identifier and avoider. It detects obstacles by emitting ultrasonic waves and measuring the time it takes for the waves to bounce back from objects, allowing the robot to determine the presence and distance of obstacles. By continuously monitoring these distances, the sensor helps the robot navigate safely, enabling it to change direction or stop to avoid collisions, thus ensuring efficient and safe movement through its environment.

![ussensor](https://github.com/tangorang3/DEElubyo--WRO--Future-Engineers/blob/6fa5bfade2096ff5f0b12540f095a6fbf293bf5d/other/Screenshot%202024-07-22%20184657.png)

## Code

## Video

*Draft*

https://youtu.be/yyAGyLI0hI4?si=qcecs3gDN43r157i

*Final*

## How to prepare the repo based on the template

_Remove this section before the first commit to the repository_

1. Clone this repo by using the `git clone` functionality.
2. Remove `.git` directory
3. [Initialize a new public repository on GitHub](https://github.com/new) by following instructions from "create a new repository on the command line" section (appeared after pressing "Create repository" button).
