---
title: "Tonic"
tags:
  - project
excerpt: "An open source project of self driving car, build with minimal hardware."
last_modified_at: 2024-08-21T22:18:26+02:00
---

## Tonic 

![demo](https://imgur.com/HAA9xJo.gif)
  
[github.com/mmajewsk/Tonic](https://github.com/mmajewsk/Tonic)

An open source project of self driving car, build for minimal price.

The Tonic project on GitHub is an open-source initiative aimed at developing an autonomous vehicle system using Python. The project includes both the software and documentation necessary to build and operate an autonomous car prototype. Here are some key points:

Objective: To create an affordable autonomous driving system using a Raspberry Pi and a single camera.
Features:
Live camera feed and recording.
Live steering system and recording.
IMU and odometry live streaming and recording.
Qt GUI client for driving and data collection.
SLAM mapping and navigation using ORB_SLAM2 with custom Python bindings.
How It Works:
The system is divided into two main parts: Tonic/control (runs on a laptop/PC) and Tonic/car (runs on the Raspberry Pi).
Communication between the control interface and the car is done via WiFi using sockets.
The car can be manually driven to collect video and steering data, which is then used to create a 3D map of the environment.
Checkpoints are defined for the car to navigate autonomously.
Getting Started:
Assemble the hardware and set up the software.
Perform a data-taking run to collect steering and video data.
Follow the guide in the Tonic/autonomous repository to enable autonomous driving.
This project is designed to be accessible and open for contributions from anyone interested in autonomous vehicle technology1.

Feel free to explore the repository for more detailed information and instructions!