---
layout: page
title: BioRob 2026 Paper
description: Real-Time 3D Proprioception for Soft Robots Using a Single Capacitive Bend Sensor.
img: assets/img/biorob-actuator.jpg
importance: 1
date: 2026-07-01
category: Academic
github: https://www.github.com/MBricq/SoftProprio3D/
tags: ["BioRob", "Soft Robotics", "Proprioception", "State Estimation", "Video"]
---

This page provides an overview of my research paper accepted for the IEEE International Conference on Biomedical Robotics and Biomechatronics (BioRob) in June 2026. The work is titled **"Real-Time 3D Proprioception for Soft Robots Using a Single Capacitive Bend Sensor"**.

### Overview

A core challenge in soft robotics is determining the exact position of the robot in a continuous state space. Traditional open-loop control methods struggle with continuous deformation and nonlinearities like cable slacking, while external camera systems are generally limited to laboratory settings.

To address this, we developed a lightweight proprioceptive approach to reconstruct the 3D pose of a cable-driven soft actuator.

Instead of relying on extensive data-driven training or complex material modifications, our method embeds a single commercial capacitive bend sensor directly inside the actuator's central core. This sensor measures the net tip bending, which is then mapped to the full actuator shape using a Piecewise Constant Curvature (PCC) model.

The code is accessible on [GitHub](https://www.github.com/MBricq/SoftProprio3D/).

### Key Results

- **Accuracy:** The sensor-based method maintains high tracking fidelity and effectively decouples state estimation from mechanical hysteresis. It achieves millimeter-level Cartesian accuracy (mean tip error of 2.48mm) and high angular precision (0.35°).
- **Efficiency:** The reconstruction algorithm executes in under 1ms, making it highly suitable for real-time applications.
- **Robustness:** The method significantly outperforms open-loop motor-based estimation, especially when mechanical disturbances (like slack) are introduced.

### Demonstration Video

The supplementary video below demonstrates the experimental setup, the real-time reconstruction process, and the validation against the optical ground-truth system.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/biorob_2026_mrbricq.mp4" class="img-fluid rounded z-depth-1" controls=true %}
    </div>
</div>
