---
layout: page
title: E-puck2 Recycling Robot
description: A miniature recycling center robot built for the "Systèmes embarqués et robotique" class at EPFL.
img: assets/img/recycling-center.jpg
importance: 3
category: Robotics
date: 2022-05-12
tags: ["C", "ChibiOS", "Control", "Coursework"]
github: https://github.com/duchoud/recycling-center
---

This project was developed for the **"Systèmes embarqués et robotique"** (Embedded Systems and Robotics) class, taught by Professor Francesco Mondada at EPFL.

Built in collaboration with Alain Duchoud, the project consists of an e-puck2 robot programmed to act as an autonomous sorting machine for a miniature recycling center.

The software architecture relies heavily on a real-time operating system (ChibiOS) and is written in C. We implemented a Finite State Machine (FSM) to handle the main control loop and prioritize tasks seamlessly. To detect and categorize the miniature "waste" objects, we integrated a computer vision pipeline utilizing the robot's onboard camera.

### Project Video

You can see the robot in action in our demonstration video below:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <div class="embed-responsive embed-responsive-16by9">
            <iframe class="embed-responsive-item" src="https://www.youtube.com/embed/ohqnYGoMsN8" allowfullscreen></iframe>
        </div>
    </div>
</div>
