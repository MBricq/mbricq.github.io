---
layout: page
title: FPGA Seizure Detector
description: An FPGA implementation of an epileptic seizure detector using spectral domain feature extraction and SVM classification.
img: assets/img/epilepsy-detector.jpg
importance: 5
category: Bio-engineering
date: 2023-02-01
tags: ["FPGA", "MATLAB", "Simulink", "VHDL", "SVM", "Signal Processing"]
github: https://github.com/MBricq/EpilepsyDetection
---

This project was completed in Spring 2023 as a semester project at EPFL, supervised by Prof. Alexandre Schmid. The primary goal was to build a robust hardware-level detector for epileptic seizures using the short-term dataset from SWEC-ETHZ.

The core of the detection algorithm relies on extracting spectral domain features using Discrete Wavelet Transform (DWT) coefficients. These features are then evaluated using linear Support Vector Machine (SVM) models to accurately identify seizure events.

To achieve hardware acceleration, the development was split into three main phases:

- **Algorithm Design:** The initial detection pipeline and models were built, trained, and simulated using MATLAB and Simulink.
- **Hardware Conversion:** The working Simulink models were translated into VHDL using the HDL Coder tool.
- **FPGA Deployment & Testing:** The design was deployed to a DE2-115 FPGA. Validation was performed using ModelSim and custom C code executed on the onboard NIOS II processor.
