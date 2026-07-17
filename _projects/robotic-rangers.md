---
layout: page
title: Robotic Rangers
description: An autonomous robotics project featuring computer vision, mapping, and advanced pathfinding.
img: assets/img/robotic-rangers.png
importance: 4
category: Robotics
date: 2024-03-20
tags: ["Computer Vision", "Coursework", "Kalman Filter", "A* Algorithm"]
github: https://github.com/MBricq/RoboticRangers
---

An autonomous robotics project focused on perception, state estimation, and navigation.

Working collaboratively, I was primarily responsible for the robot's visual processing and spatial awareness stack. My main contribution was developing the **computer vision** pipeline to allow the robot to accurately perceive its environment and extract critical features.

To translate that visual data into reliable, autonomous movement, I also implemented:

- **Mapping Algorithms:** Building and updating a dynamic spatial representation of the robot's surroundings based on incoming sensor data.
- **State Estimation:** Applying a **Kalman Filter** to fuse noisy sensor readings, allowing the robot to continuously track its true position and velocity with high accuracy.
- **Pathfinding:** Utilizing the **A\*** (A-star) search algorithm to compute the optimal, collision-free trajectory through the generated map.
