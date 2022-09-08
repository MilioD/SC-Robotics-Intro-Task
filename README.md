# Space Concordia Robotics Software-Team Intro Task

Catkin workspace for ROS software training SC Robotics intro task (Software Training v4).
This ROS package uses a publisher node written in python and the subscriber node in C++ and was made on Ubuntu 20.04.05 LTS with ROS noetic.
Made using the work from [ROS Tutorials](http://wiki.ros.org/ROS/Tutorials#Beginner_Level).

### Build Instructions

To build the package run the following commands :
```
cd ~/SC-Robotics-Software-Intro-Task/
catkin_make
```

### How to run

1.  Initialize roscore :
```
roscore
```
2.  Source the workspace's setup file :
```
cd ~/SC-Robotics-Software-Intro-Task/
source ./devel/setup.bash/
```
3.  Run the publisher :
```
rosrun pub-sub_task talker.py
```
4.  Run the subscriber :
```
rosrun pub-sub_task listener
```