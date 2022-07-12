# Introduction

Ever wanted to explore what’s beneath the river Brahmaputra or what secrets our delightful lakes are hiding. If yes, then welcome to team antahsagri where we find answers to these questions through our Semi Autonomous Underwater vehicle, Antahsagari. Our team works on diverse modules from semi-AUV designing to its navigation, incorporating image processing and a versatile framework ROS.


## About us:
Currently we are working on  Antahsagari 3.0  which has six thrusters for better stability and maneuverability, includes robotic arms for underwater sample collection as well as carrying out underwater repairs, and will overcome other challenges faced by old models.


Antahsagri 2.0 was an underwater, remotely operated vehicle (ROV)  developed by a multidisciplinary student group at IIT Guwahati to facilitate research and development in underwater robotics. 

Antahsagri traces its origin to June 2019 when a group of students from varied engineering streams came together to deploy their skills. The team developed its first vehicle, Antahsagri 1.0, in November 2019, overcoming hurdles like cost, manufacturability, efficient design, and limited time. The underwater nature imposes a number of challenges for navigation like depth pressure, water leakage, stability related issues, poor underwater lighting, etc. We are determined to develop cutting-edge technology to overcome these challenges.  Antahsagri 2.0  has majorly improved upon the previous versions in terms of weight optimization, reliability, endurance, speed, and high modularity. We aim to make it more versatile and adaptive to make marine research and analysis effortless and prolific in the future.

[**Click_Here**](https://www.youtube.com/watch?v=LpOH96YZ9nc) **to watch the demonstration video.**

<a href="url"><img src="https://github.com/MonuKumar1/Antahsagari-3.0/blob/master/3D%20Design/images/Antah3.0.png" ></a>

## AIM:

- The aim of the project is to basically explore underwater world.
- We are trying to analyse the impact of urbanisation on structure and function of river system using the chemical data extracted from the water using sensors.
- It can also be used as a survey platforms to map sea floor or characterise physical, chemical, biological properties of water.
- It can be used to perform infrastructure inspections of pipeline systems so that divers are not put in harm's way.


## Physical architecture:

Antahsagri 3.0  is an Semi-Autonomous Underwater Vehicle, designed to explore the underwater world and collect data for research and analysis. It is equipped with several sensors:

- 6 Thrusters T100
- 6 Basic Esc
- 1 Bar30 pressure sensor
- 1 Temperature Sensor
- 2 Leak sensors
- 2 Lumen Subsea Lights
- 1 Raspberry Pi , used as a companion computer
- 1 camera
- 1 servo for the camera tilt
- 1 PixHawk with internal 9 DOF IMU


The small size of the Antahsagri and its high manoeuvrability is perfect to achieve exploration missions in tiny places. Also, its wide variety of sensors make the automation easier.

## Methodology

We are using ArduSub which works seamlessly with Ground Control Station software that can monitor vehicle telemetry and perform powerful mission planning activities. It also benefits from other parts of the ArduPilot platform, including simulators, log analysis tools, and higher level APIs for vehicle management and control.ArduSub is the 'brains' of the ROV. The Raspberry Pi Companion Computer runs software that relays communications between the autopilot and QGroundControl via Ethernet communications. The Companion software also streams HD video to QgroundControl. We are using SITL for simulation.SITL is a simulator that allows you to run ArduSub without any hardware.

Below is a typical diagram of hardware components on the ROV and their connections.
<p align="center">
  <img src="https://www.ardusub.com/images/hardware-diagram.png">
</p>

