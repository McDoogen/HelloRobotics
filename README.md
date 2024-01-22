# HelloRobotics

Hello! The purpose of this project is to provide a "Hello World" interation with ROS and Robotics across a few platforms.

There will be three Nodes interacting with each other each with a "Button" and an "LED"
- Ubuntu Frame Snap on a Raspberry Pi
- uROS on a Pi Pico
- ROS on a PC

We will be using ROS 2, Iron Irwini



# Environment Setup

## Setup multipass environment
`multipass launch 22.04 --cpus 4 --disk 20G --memory 8G --name ros2-iron`

## Setup ROS 2 Development Environment
`https://docs.ros.org/en/iron/Installation/Ubuntu-Install-Debians.html`

## Source ROS 2 Development Environment (On every Startup)
`source /opt/ros/iron/setup.bash`

## Automatically Source ROS 2 Development Environment
`echo "source /opt/ros/iron/setup.bash" >> ~/.bashrc`