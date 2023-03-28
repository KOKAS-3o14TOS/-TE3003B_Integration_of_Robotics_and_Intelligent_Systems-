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
  This week will introduce the teaching team and the basics of dynamical systems.
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
  
  ### Week 2: (Uncertainty in mobile robotics)  
  This week will introduce some basics of probabilities.
  #### Session 1:
  * Introduction to probabilities
    -	Preliminaries (Basics).
    -	Discrete random variables.
    -	Continuous random variables.
    -	Distributions (Uniform, Gaussian)
  *	Linearisation – Fundamentals

  #### Session 2:
  * Ellipsoid of confidence.
  *	Mobile robot localisation (dead reckoning) in presence of uncertainties
  
  **Mini challenge:**: 
  * Linearise of a dynamical system and compare its behaviour with the original nonlinear real system.
  *	Mobile robot linearisation.
  *	Plot the confidence ellipsoid of a mobile robot. Use the multiple point navigation.
  
  **Requirements:** Requirements of Session 1.

  ### Week 3: Q&A
  This week will be dedicated to a Q&A session.
  #### Session 1:
  * Q&A Session
  
  #### Session 2:
  * Q&A Session.
  
  **Requirements:** Requirements of Session 1.
  
  ### Week 4: Reactive navigation
  This week will introduce the concept of reactive navigation for robotics.
  #### Session 1:
  * •	Exteroceptive sensors.
  *	Obstacle avoidance
  *	Obstacle avoidance algorithms: 
    - Bug 0, Bug 1, Bug 2.
  
  #### Session 2:
  * Q&A Session.
  
  **Requirements:** Requirements of Session 1 and Session 3.
  
  **Mini challenge:**: 
  * Implementation of obstacle avoidance algorithms Bug 0 and Bug 2 in simulation (Gazebo) and with the real robot.
  
  
  ### Week 5: Final Challenge
  This week will be dedicated to a Q&A session.
  
  #### Session 1:
  * Q&A Session.
  #### Session 2:
  * Q&A Session.
  
  **Requirements:** Requirements of Session 1.

  ### Week 6: Sources of information
  This week the concept of Kalman filter will be introduced.
  
  #### Session 1:
  * Bayes Filter.
  *	Kalman Filter
  *	Kalman Filter for map-based localisation (2D).

  #### Session 2:
  * Kalman Filter for map-based localisation (2D).
  *	Camera based localisation for mobile robots.
    -	Aruco markers
    -	Visual localisation of mobile robots using Aruco markers
    -	Kalman filter for map-based localisation in 3D. Kalman filter estimation by combining visual localization with encoder information.

  
  **Requirements:** Requirements of Session 1.


  ### Week 7: Final Challenge
  This week the Final Challenge will be presented.
  
  #### Final Challenge
  *	Mobile robots’ navigation
  *	Camera based Kalman filter localisation for the Puzzlebot. (Steps)
    1.	Multiple point navigation with obstacle avoidance. Use Dead reckoning localization.
    2.	Multiple point navigation no obstacles, using visual based localisation.
    3.	Multiple point navigation no obstacles, using Kalman filter estimation.
    4.	Multiple point navigation with obstacles, using Kalman filter estimation. 

  ### Week 8: Final Challenge
  This week will be dedicated to a Q&A session.
  
  #### Session 1:
  * Q&A Session.
  #### Session 2:
  * Q&A Session.

  ### Week 9: Grading
  This week will be dedicated to a Q&A session.
  
  #### Session 1:
  * Q&A Session.
  #### Session 2:
  * Grading.
