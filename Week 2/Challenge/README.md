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

# Week 1: Mini challenge

* In this folder, the student will find the neccessary files for Mini challenge 1.
* The instruction for this challenge can be found inside the presentation *MCR2_MiniChallenge1*


## Description
This activity is intended for the student to review the concepts introduced in this week.

  * The challenge is divided into two parts: 
    * Part 1:
      * Development of a kinematic simulator for the Puzzlebot robotic platform, using the kinematic model of a nonholonomic robot.
    * Part 2: 
      * Analysis of the uncertainties present in the real, gazebo simulation, and kinematic simulation of the Puzzlebot.

## Notes
  - The *STL Files* folder, contains the neccessary .stl £D files of the Puzzlebot. 
  - These fles ar intended to be used for the RVIZ kinematic simulator.
      * MCR2_1000_0_Puzzlebot : Full Puzzlebot model (including wheels)
      * MCR2_1000_1_1_Wheel_Coupler_2 : Assembly of the Puzzlebot wheels.
      * MCR2_1000_13_Chassis : Model of the Puzzlebot chassis (not including wheels)

  - The gazebo Simulator can be found in the folder "Puzzlebot_Gazebo_Simulator"

  - The step file of the "Puzzlebot_base" can be found in the folder "Puzzlebot_Step_Files".

  - Remember to make the nodes executable using the the following command inside the catkin_ws/src/basic_comms/src and catkin_ws/src/basic_comms/src
 folders 
```
 chmod +x signal_generator.py
 chmod +x process.py
```

## Rules
  * This is challenge not a class. The students are encouraged to research, improve tune explain their algorithms by themselves.
  * MCR2(Manchester Robotics) Reserves the right to answer a question if it is determined that the questions contains partially or totally an answer.
  * The students are welcomed to ask only about the theoretical aspect of the classed.
  * No remote control or any other form of human interaction with the simulator or ROS is allowed (except at the start when launching the files).
  * It is forbidden to use any other internet libraires with the exception of standard libraires or NumPy.
  * If in doubt about libraires please ask any teaching assistant.
  * Improvements to the algorithms are encouraged and may be used as long as the students provide the reasons and a detailed explanation on the improvements.
  * All the students must be respectful towards each other and abide by the previously defined rules.
  * Manchester robotics reserves the right to provide any form of grading. Grading and grading methodology are done by the professor in charge of the unit.
  
