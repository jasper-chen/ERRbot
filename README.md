# ERRbot

## Description

ERRbot stands for Emergency Response Robot, which is the project name for the final class project for Computational Robotics at Olin College Fall 2014. This code repository contains code for a robot which searches and locates known objects in an enclosed space. The robot is a revamped vaccuum cleaner, which comes equipped with an onboard laser scanner, a camera and a Raspberry Pi to control its movements based on the sensor readings. Our goal was to program the robot to navigate and search through an enclosed space and identify known objects.

## 

From the start, our team mutually agreed to divide tasks by path planning, map making and object recognition. I worked on the navigation algorithm of the robot, which includes creating waypoints and sending the correct movements to the 

## To Run

```
roslaunch neato_node bringup.launch host:=IP_ADDRESS_OF_THE_PI
rosrun ERRbot ERRbot.launch
roslaunch neato_2dnav hector_mapping_neato.launch
(later) roslaunch hector_slam hector_mappping.launch 

```

## Neccessary Installs 

```
Install hector_slam and hector_worldmodel

sudo apt-get install ros-hydro-hector-slam
sudo apt-get install ros-hydro-hector-worldmodel

```
## Team

Jasper Chen
Claire Diehl 
Amanda Sutherland
