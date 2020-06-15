# MOCAP4ROS2

This project provides support for ROS2 integration with Vicon cameras (MOCAP systems based on vision) and Technaid TechMCS IMUs (MOCAP systems based on motion sensors).

The project [MOCAP4ROS2](https://rosin-project.eu/ftp/mocap4ros2) is funded as a Focused Technical Project by [ROSIN](http://rosin-project.eu/).


<a href="http://rosin-project.eu">
  <img src="http://rosin-project.eu/wp-content/uploads/rosin_ack_logo_wide.png"
       alt="rosin_logo" height="60" >
</a>

Supported by ROSIN - ROS-Industrial Quality-Assured Robot Software Components.  
More information: <a href="http://rosin-project.eu">rosin-project.eu</a>

<img src="http://rosin-project.eu/wp-content/uploads/rosin_eu_flag.jpg"
     alt="eu_flag" height="45" align="left" >  

This project has received funding from the European Union’s Horizon 2020  
research and innovation programme under grant agreement no. 732287.

***

<p align="center"> 
<img align="center" src="https://github.com/IntelligentRoboticsLabs/MOCAP4ROS2/blob/master/resources/mocap4ros_arch.png" 
    alt="mocap4ros_arch" width="100%">
</p>


## Guide

[![Build Status](https://travis-ci.com/IntelligentRoboticsLabs/MOCAP4ROS2.svg?branch=master)](https://travis-ci.com/IntelligentRoboticsLabs/MOCAP4ROS2)

To use this project is important follow the next steps.
First of all, we have to download the dependencies packages. We will use **vcs-tool**
  ```
    cd [ros2_ws]/src
    git clone https://github.com/IntelligentRoboticsLabs/mocap4ros2_project.git
  ```
  If you want to install the vicon packages you have to run the next command:
  ```
    vcs import < mocap4ros2_project/vicon.repos
  ```
  If you want to install the technaid packages you have to run the next command:
  ```
    vcs import < mocap4ros2_project/technaid.repos
  ```

### Vicon

Read about Vicon prerequesites, instalation and usage guide [here](https://github.com/IntelligentRoboticsLabs/MOCAP4ROS2/blob/master/mocap4ros_drivers/vicon2_driver/README.md).

### TechMCS IMUs

Read about TechMCS IMUs prerequesites, instalation and usage guide [here](https://github.com/IntelligentRoboticsLabs/MOCAP4ROS2/blob/master/mocap4ros_drivers/TechMCS_ROS2/README.md).
