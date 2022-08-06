# SM2022_AI_Task-04
# Use Turtlebot3 with SLAM approach to create and save a map
<br/>

![00](https://user-images.githubusercontent.com/101488769/183163488-bc7b9d45-897b-4728-9eeb-0e712f8fd050.gif)
<br/>

## Table of Contents:-
* [1- Download and Install Ubuntu on PC](#1-Download-and-Install-Ubuntu-on-PC)
* [2- Install ROS on Remote PC](#2-Install-ROS-on-Remote-PC)
* [3- Install Dependent ROS Packages](#3-Install-Dependent-ROS-Packages)
* [4- Install TurtleBot3 Packages](#4-Install-TurtleBot3-Packages)
* 

## 1-Download-and-Install-Ubuntu-on-PC:
### 1.1 Download the proper `Ubuntu 20.04 LTS Desktop` image for your PC from the links below.
* [Ubuntu 20.04 LTS Desktop image (64-bit)](https://releases.ubuntu.com/20.04/)
### 1.2 Follow the instruction below to install Ubuntu on PC:
* [Install Ubuntu desktop](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
 <br/>

## 2-Install-ROS-on-Remote-PC:
Open the terminal with `Ctrl` + `Alt` + `T` and enter below commands one at a time.<br/>
In order to check the details of the easy installation script.<br/>
`$ sudo apt update` <br/>
`$ sudo apt upgrade` <br/>
`$ wget https://raw.githubusercontent.com/ROBOTIS-GIT/robotis_tools/master/install_ros_noetic.sh` <br/>
`$ chmod 755 ./install_ros_noetic.sh`<br/>
`$ bash ./install_ros_noetic.sh`<br/>

## 3-Install-Dependent-ROS-Packages:
`$ sudo apt-get install ros-noetic-joy ros-noetic-teleop-twist-joy \`<br/>
  `ros-noetic-teleop-twist-keyboard ros-noetic-laser-proc \`<br/>
  `ros-noetic-rgbd-launch ros-noetic-rosserial-arduino \`<br/>
  `ros-noetic-rosserial-python ros-noetic-rosserial-client \`<br/>
  `ros-noetic-rosserial-msgs ros-noetic-amcl ros-noetic-map-server \`<br/>
  `ros-noetic-move-base ros-noetic-urdf ros-noetic-xacro \`<br/>
  `ros-noetic-compressed-image-transport ros-noetic-rqt* ros-noetic-rviz \`<br/>
  `ros-noetic-gmapping ros-noetic-navigation ros-noetic-interactive-marker`<br/>
  

## 4-Install-TurtleBot3-Packages:
Install TurtleBot3 via Debian Packages.<br/>
`$ sudo apt install ros-noetic-dynamixel-sdk`<br/>
`$ sudo apt install ros-noetic-turtlebot3-msgs`<br/>
`$ sudo apt install ros-noetic-turtlebot3`<br/>
