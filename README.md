# ROS2-Self-Driving-Car-Using-OpenCV-AI
Self-Driving Car Using Computer Vision and AI

# ROS2 Prius Self Driving Car  using AI/Deeplearning and Computer Vision


<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#About-this-Repository">About This Repository</a></li>
    <li><a href="#Using-this-Repository">Using this Repository</a></li>
    <li><a href="#Course-Workflow">Course Workflow</a></li>
    <li><a href="#Features">Features</a></li>
    <li><a href="#Pre-Course-Requirments">Pre-Course Requirments</a></li>
    <li><a href="#Repository-Tree">Repository Tree</a></li>
  </ol>
</details>

## About this Repository
A tesla Like Car in ROS2 will follow lane , Use AI to classify Sign Boards and perform Object tracking to act on the sign boards and set speed respectively

----
## Using this Repository
----
**Docker**:

 [![alt text](https://github.com/HaiderAbasi/ROS2-Path-Planning-and-Maze-Solving/blob/master/images/linux.png)](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/docker/running_on_linux.md "Follow the guide to setup docker on Linux")&nbsp;&nbsp;
 [![alt text](https://github.com/HaiderAbasi/ROS2-Path-Planning-and-Maze-Solving/blob/master/images/windows.png)](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/docker/running_on_windows.md "Follow the guide to setup docker on Windows 10")&nbsp;&nbsp;


**Ubuntu-20.04**: 

----
## Course Workflow
#### **Ros Package**
* World Models Creation
* Prius OSRF gazebo Model Editing
* Nodes , Launch Files
* SDF through Gazebo
* Textures and Plugins in SDF

#### **Computer Vision**
* Perception Pipeline setup
* Lane Detection with Computer Vision Techniques
* Traffic Light Detection Using Haar Cascades
* Sign and Traffic Light Tracking using Optical Flow
* Rule-Based Control Algorithms

#### **DeepLearning**
* Sign Classification using (custom-built) CNN
---
## Features
* **Prius Hybrid Car**
  -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/the_car.gif)

* **Satellite Navigation (NEW!)**
    * **Stage 1: Localiation**

      -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/Sat_Nav/1_localization.gif)

    * **Stage 2: Mapping**

      -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/Sat_Nav/2_mapping.gif)

    * **Stage 3: Path-Planning**

      -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/Sat_Nav/3_pathplanning.gif)

    * **Stage 4: Motion-Planning**

      -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/Sat_Nav/4_motionplanning.gif)
  
* **Lane Following**
  -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/lane_detection.gif)
* **Sign Board Detection**
  - ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/traffic_signs_boards.gif)
* **Traffic Signal Recognition**
  - ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/traffic_signal.gif)

* **T-Junction Navigation**
  - ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/j_turning.gif)

* **The World**
  -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/world.gif)

* **Custom Models**
  -  ![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/custom_models.gif)

----
## Pre-Course Requirments

**Software Based**
* Ubuntu 20.04 (LTS)
* ROS2 - Foxy Fitzroy
* Python 3.6
* Opencv 4.2
* Tensorflow 2.14

**Skill Based**
* Basic ROS2 Nodes Communication
* Launch Files
* Gazebo Model Creation
* Basic OpenCV Usage
* Motivated mind :)
---

## Repository Tree
> Explaining repository structure (i.e important files and their functions).

![alt text](https://github.com/noshluk2/ROS2-Self-Driving-Car-AI-using-OpenCV/blob/main/Images_videos/ROS2_SDC_Tree.png)


