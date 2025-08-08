---
layout: post
title: "FSDS setting"
date: 2025-08-07
---
-Using WSL2 Ubuntu 20.04 ros1 noetic
-Every time rebooted, check ip adress using window terminal commad "hostname -I"
-and change the settings.json file ip adress
-and in ubunut terminal using nano ~/.bashrc then source ~/.bashrc


-terminal 1: run roscore
-terminal 2: go to "Formula-Student-Driverless-Simulator/ros" directory and run the following
            -catkin init 
            -source devel/setup.bash
            -roslaunch fsds_ros_bridge fsds_ros_bridge.launch
-terminal 3: go to "Formula-Student-Driverless-Simulator/ros" directory and run the following
            -roslaunch fsds_ros_bridge rviz.launch

-When refreshing the settings refresh the rosbridge terminal first!