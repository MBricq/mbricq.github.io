---
layout: page
title: Ringo-walks
description: ROS-based control and estimation for a walking robot platform, built in collaboration with Tommaso Scudeletti.
img: assets/img/ringo.jpeg
importance: 2
category: research
date: 2026-07-15
tags: ["ROS", "Control", "Estimation", "Robotics"]
github: https://github.com/ScudeT/Ringo-walks
---

# Ringo-walks

**Ringo-walks** is a collaborative robotics project developed during my Ph.D. at Politecnico di Milano, built alongside my colleague [Tommaso Scudeletti](https://github.com/ScudeT). The project focuses on deploying robust locomotion control for a walking robot platform utilizing a modern Robot Operating System (ROS) architecture.

## My Contribution: Low-Level Control & Estimation

While developing complex robotic systems requires a strong collaborative effort, my primary focus on this project centered around the **low-level control** and **state estimation** pipelines within the ROS framework.

Key aspects of my work included:

- **State Estimation:** Implementing sensor fusion and estimation algorithms to accurately determine the robot's pose, velocity, and orientation in real-time.
- **Low-Level Control Architecture:** Developing the control loops that interface directly with the robot's hardware. This involved bridging the gap between high-level trajectory planning and the actual motor commands required to execute those movements smoothly.
- **ROS Integration:** Structuring the control and estimation nodes within the ROS ecosystem, ensuring real-time performance and efficient message passing between the hardware interfaces and the higher-level logic.

## Source Code

The complete source code for the project, including the ROS packages and implementation details, is available on GitHub:

[ScudeT/Ringo-walks repository](https://github.com/ScudeT/Ringo-walks)
