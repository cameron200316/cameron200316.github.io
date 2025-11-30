---
layout: default
title: Projects
permalink: /projects/
---
[Home](/) | [My Career](/myCareer/) | [GitTor](/gitTor/) | [My Projects](/projects/) | [Documents](/documents/) | [LinkedIn](https://www.linkedin.com/in/camerongilbertson/)

# Projects
## CNN Hardware Accelerator for Image Classification
Details: 
* Class: CPRE-487 Hardware Design for Machine Learning
* Semester: Fall 2025
* Total Time: 110 hours

This project involved designing and implementing a hardware accelerator for a convolutional neural network (CNN). The hardware used was ZedBoard, and the goal was to achieve a significant speedup. Our approach utilized four MAC units working simultaneously, along with switchable filter banks, allowing the next weights to be loaded during computations, thereby saving downtime. Our results achieved a total inference time reduction from approximately 30 seconds to around 550 milliseconds!

My contribution involved debugging the hardware in behavioral VHDL. I also assisted in debugging the software implementation in C++ and our helper scripts in Python. I gained a lot of experience in coding languages that I was previously less familiar with, as well as debugging hardware using Vivado ILAs.  

## Forwarded Pipelined Processor
Details: 
* Class: CPRE-381 Computer Organization and Assembly Level Programming
* Semester: Spring 2024
* Total Time: 80 hours

This project was designed and implemented a pipelined processor. My partner and I decided to handle data hazards using a mix of forwarding and flushing. We also implemented a naive machine learning approach for our branch prediction. Our strategy was to predict the same branch outcome as the previous branch. This strategy works well with nested loops because it enters the loop while needed and then quickly exits all the loops correctly when finished. 

My contribution involved the full integration of both the hardware and the branch prediction logic. I learned a great deal about debugging hardware, as well as the importance of using proper coding documentation when working on such a large-scale project.

## Autonomous Ice Cream Truck
Details: 
* Class: CPRE-288 Embedded Systems 1 
* Semester: Fall 2023
* Total Time: 45 hours

The autonomous ice cream truck was not an actual ice cream truck, unfortunately. This was my group's real-life application for our final project. The goal of the project was to have our CyBot navigate a course autonomously and identify the correct objects while avoiding the incorrect ones. We gave each of these objects real-life applications. Inside the course, we had the following objects: 

* Holes - Lakes
* Boundaries - Park Limits
* Tall Wide Objects - Trees
* Short Wide Objects - Rocks
* Tall Skinny Objects - Children

So our objective was to find the children and sell them ice cream cones. This involved using the IR and PING sensors for object detection, and then utilizing decision trees to determine how the CyBot should behave in specific scenarios. 

My contribution was in the decision tree and bump detection. The decision tree required extensive testing to determine the optimal turning angle, taking into account the position of trees, rocks, lakes, and park boundaries. Overall, I gained extensive experience in C, as well as embedded programming. 
