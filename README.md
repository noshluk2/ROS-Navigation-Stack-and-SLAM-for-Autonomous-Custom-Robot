# ROS Autonomous Driving and Path Planning SLAM with TurtleBot3

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#About-this-Repository">About This Repository</a></li>
    <li><a href="#Using-this-Repository">Using this Repository</a></li>
    <li><a href="#Course-Workflow">Course Workflow</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="#Pre-Course-Requirments">Pre-Course Requirments</a></li>
    <li><a href="#Link-to-the-Course">Link to the Course</a></li>
    <li><a href="#Notes">Notes</a></li>
    <li><a href="#Instructors">Instructors</a></li>
    <li><a href="#License">License</a></li>
  </ol>
</details>

## About this Repository
This is repository for the course **ROS Navigation Stack and SLAM for Autonomous Custom Robot** availble at Udemy . Complete source code is open sourced . Notes are also attached in root of the repository.

 ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/main_cover.png)
- **[[Get course Here]](https://www.udemy.com/course/robotics-with-ros-build-custom-robots-from-scratch/?couponCode=APRIL_END)**
----
## Using this Repository
* Move into your workspace/src folder
 ```
 cd path/to/ros1_ws/src/
##e.g cd ~/catkin_ws/src/
  ```
* Clone the repository in your workspace
```
git clone https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot
```


* Perform make and build through catkin
 ```
 cd /path/to/workspace_root/
 ##e.g ~/catkin_ws/
 catkin_make
 ```
 
* Source your Workspace in any terminal you open to Run files from this workspace ( which is a basic thing of ROS )
```
source /path/to/catkin-ws/devel/setup.bash
```
- (Optional for Power USERs only) Add source to this workspace into bash file
 ```
echo "source /path/to/catkin-ws/devel/setup.bash" >> ~/.bashrc
 ```
  **NOTE:** This upper command is going to add the source file path into your ~/.bashrc file ( Only perform it once and you know what you are doing).This will save your time when running things from the Workspace

----
## Course Workflow
- We will start by creating a custom robot named as Explorer Bot .Two wheel Differential Drive type , created from scratch using URDF containing joints, links are which are going to be explored in depth. Once the robot will be created we will add Gazebo Plugins into it  ( Differential Drive and Laser Scanner ) into URDF of our robot  . This will lead us to driving the robot and reading laser scan values from inside of simulation.

- After understanding all the basics of with a Custom mobile Robot we will move to a very well known ROS package SLAM  which contains multiple nodes for mapping a environment , we will utilize Gmapping Node with lidar sensor as a source . Then we will bring in a 3D mesh of a pipeline of which we create a map.

- After that we will create a room for Autonomous Navigation using Gazebo Model Builder tool. Out robot will perform Autonomous driving using Navigation Stack and Path Planning algorithms from Navigation Stack .




---
## Features
* **URDF Explorer Bot Creation** 
  -  ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/urdf_bot_creation.gif)
* **Gazebo Physical Properties Calculations** 
  -  ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/gazebo_physicalProperties.gif)
* **Gazebo simulation Plugins** 
  -  ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/Simulating_plugins.gif)
* **Pipe Line Map Creation using SLAM** 
  -  ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/PipeLine_mapping.gif)
* **Custom Gazebo Room Navigation**
  - ![alt text](https://github.com/noshluk2/ROS-Navigation-Stack-and-SLAM-for-Autonomous-Custom-Robot/blob/master/Image_resources/room_navigation.gif)



----
## Pre-Course Requirments 

**Software Based**
* Ubuntu 20.04 (LTS)
* ROS1 - Noetic
---
## Link to the Course
Below is a discounted coupon for people who want to take the course in which more explaination to this code has been added

**[[Get course Here]](https://www.udemy.com/course/robotics-with-ros-build-custom-robots-from-scratch/?couponCode=APRIL_END)**

----
## Notes
 We have uploaded all the notes made during the lectures of the course so you can get more out of this repository with the instructors Notes. A seperate folder named as **Notes** contain a single PDF carrying all the notes in the root of this repository

----

## Instructors

Muhammad Luqman (ROS Simulation and Control Systems) - [Profile Link](https://www.linkedin.com/in/muhammad-luqman-9b227a11b/)  

----
## License

Distributed under the GNU-GPL License. See `LICENSE` for more information.
