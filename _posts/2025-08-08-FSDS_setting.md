---
layout: post
title: "FSDS setting"
date: 2025-08-07
---
- Using WSL2 Ubuntu 20.04 ros1 noetic
- Every time rebooted, check ip adress using window terminal commad ipconfig eth4


- terminal 1: run roscore
- terminal 2: go to "Formula-Student-Driverless-Simulator/ros" directory and run the following
            - catkin init 
            - source devel/setup.bash
            -  roslaunch fsds_ros_bridge fsds_ros_bridge.launch host_ip:= <paste ip address>
- terminal 3: go to "Formula-Student-Driverless-Simulator/ros" directory and run the following
            - roslaunch fsds_ros_bridge rviz.launch

- When refreshing the settings refresh the rosbridge terminal first!