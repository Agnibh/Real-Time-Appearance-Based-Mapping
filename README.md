# Real Time Appearnace Based Mapping-Project

This project was developed for the course [Udacity Robotics Software Engineer Nanodegree Program](https://www.udacity.com/course/robotics-software-engineer--nd209).

<img src="SLAM.gif"/>

Created a 2D occupancy grid and 3D octomap from a simulated environment using our own robot with the RTAB-Map package.

## Dependencies for Running Locally
* cmake >= 3.7
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gazebo

## Build Instructions

* Create a catkin_ws, feel free to skip if you already have one!

     $ cd /home/workspace/

     $ mkdir -p /home/workspace/catkin_ws/src/

     $ cd catkin_ws/src/

     $ catkin_init_workspace

     $ cd ..

* Clone the package in catkin_ws/src/

     $ cd /home/whttps://github.com/Agnibh/Go-Chase-It-.git

* Build the  package

     $ cd /home/workspace/catkin_ws/ 

     $ catkin_make

* After building the package, source your environment

     $ cd /home/workspace/catkin_ws/

     $ source devel/setup.bash

* Once the package has been built, you can launch the simulation environment using

     $ roslaunch my_robot world.launch

* SLAM using

     $ cd /home/workspace/catkin_ws/

     $ source devel/setup.bash

     $ roslaunch my_robot mapping.launch

