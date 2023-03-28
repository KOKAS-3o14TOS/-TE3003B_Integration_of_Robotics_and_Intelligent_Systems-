<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ManchesterRoboticsLtd/TE3003B_Integration_of_Robotics_and_Intelligent_Systems/blob/main/Misc/Logos/Logotipo%20Vertical%20Bco_Transparente.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/TE3003B_Integration_of_Robotics_and_Intelligent_Systems/blob/main/Misc/Logos/Logotipo%20Vertical%20Azul%20transparente.png">
  <img alt="Shows ITESM logo in black or white." width="160" align="right">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/ManchesterRoboticsLtd/TE3003B_Integration_of_Robotics_and_Intelligent_Systems/blob/main/Misc/Logos/MCR2_Logo_White.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/TE3003B_Integration_of_Robotics_and_Intelligent_Systems/blob/main/Misc/Logos/MCR2_Logo_Black.png">
  <img alt="Shows MCR2 logo in black or white." width="150" align="right">
</picture>

---
# TE3003B: Integration of Robotics and Intelligent Systems

  ## Introduction
   * This course, developed by Manchester Robotics ltd. (MCR2), aims to provide students with understanding of modern autonomous systems.
   * This course is divided into ten sessions, carefully designed for the user to learn about the problems of localisation and provide students with an overview on main topics encountered in autonomous systems field such as localization techniques, navigation, and intelligent path-planning.
   * This course will be based on challenges to make the student aware of the problems faced during the implementation of advanced intelligent algorithms in robotics.
   * This branch contains all the presentations, activities and files required for the “TE3003B: Integration of Robotics and Intelligent Systems” course of the Tec de Monterrey.
   * This repository is organised by sessions, each subfolder contains all the neccesary files for each one of the activities of this course.

   
## General Information
* Duration: 10 Weeks
* Classes: Tuesday and Friday  (1 – 3 PM)
* Starts: 28 March.
* Ends: 1 June
* ZOOM Link Classes: https://itesm.zoom.us/j/4779422764

## Live Sessions (Recordings)
https://drive.google.com/drive/folders/1zwf-i3HS0DGVfw6-EP8dxm5uoH7hNtVi?usp=sharing

 
## General Requirements
General requirements. Please be aware that a set of requirements especific for each session will be shown in each session subsection (Some items may be repeated).
* Computer with access to Zoom (online classes).
* Computer with Ubuntu 18.04 and ROS Melodic.
* Knowledge of ROS.
* Knowledge of Windows. 
* Basic knowledge of Ubuntu (recommended).
* Basic understanding of robotics (recommended).
* Access to a Puzzlebot Jetson/Lidar Edition. 


  <br/><br/><br/>
  <picture>
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/ManchesterRoboticsLtd/TE3003B_Integration_of_Robotics_and_Intelligent_Systems/blob/main/Misc/Logos/course.png">
  <img alt="course info." width="200" align="center">
  </picture>
  <br/><br/>


## Weekly Sessions

  ### Week 1: (Mobile Robots – Fundamentals)
  This week will introduce the teaching team and the basics of ROS.
  #### Session 1:
  * Course Introduction.
  *	Dynamical Systems.
  *	State space representations.
  *	Linear and Nonlinear systems.
  *	Discrete Time Systems.

  #### Session 2:
  *	Introduction to mobile robotics.
  *	Kinematics for a differential drive mobile robot.
  *	Proprioceptive and exteroceptive sensors.
  *	Dead Reckoning (Encoder based localisation)
  *	Point to point navigation.

  
  **Mini challenge:** 
  *	Move the Puzzlebot in a straight line (open loop) from point A to point B, for a specified time. Repeat the experiment 15 to 20 times and record the position data. 
  * Turn the robot from an initial angle (open loop), for a specific time to a final angle, and record the position data. Repeat the experiment 15 to 20 times.
  *	The experiment must be run with the real robot, Gazebo and kinematic simulation.
  *	Multiple point navigation for the different paths designed. Repeat experiment multiple times.
  
  **Requirements:** Computer with access to Zoom, Ubuntu 18.04 and ROS Melodic Installed (Full installation).
  
  ### Week 2: (ROS Practicalities)  
  This week will introduce some useful ROS practicalities.
  #### Session 1:
  * ROS Namespaces
  * ROS Parameter Server
  * Activity 1: Parametrise previous nodes
  #### Session 2:
  * ROS Custom Messages
  * Q&A
  
  **Mini challenge:**: P/PI Controller from scratch to a 1st order simulated system.
  
  **Requirements:** Requirements of Session 1.

  ### Week 3: ROS-Hardware Communication
  This week will introduce hardware communication between ROS and the Hackerboard using ROSSerial.
  #### Session 1:
  * Motor Control Theory
  * ROS Serial
  * Arduino
  * ROS Serial/Arduino Communication.
  
  **Mini challenge:** Motor Speed regulation using ROS.
  #### Session 2:
  * Q&A Session.
  
  **Requirements:** Requirements of Session 1, Installation of the Arduino IDE and the Rosserial package in the VM or Ubuntu (See instructions on Session2 MCR2_Arduino_IDE_Confirguration), Access to Hackerboard and a MCR2 DC motor.
    * In case you have no access to the Hackeborad, the hardware can be replaced for an Arduino Mega, a L298n Motor Driver and a DC motor brushed with encoder (More information MCR2_General_Information_Prerequisites).
  
  ### Week 4: ROS Data Acquisition
  This week will introduce how to acquire data between ROS and the Hackerboard using ROSserial.
  #### Session 1:
  * Encoder Basic Theory
  
  **Mini challenge:** Acquire data from the encoders using Arduino.
  **Final Challenge:** PID Controller using ROS and compare with simulation.

  
  #### Session 2:
  * Q&A Session.
  
  **Requirements:** Requirements of Session 1 and Session 3.
  
  ### Week 5: Final Challenge
  Final Challenge presentation week.
  
  **Final Challenge:**: PID Controller using ROS and compare with simulation.
  #### Session 1:
  * Q&A Session.
  #### Session 2:
  * Final Challenge.
  
  **Requirements:** Requirements of Session 1 and Session 3.

  Hola
