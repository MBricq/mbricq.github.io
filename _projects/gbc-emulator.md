---
layout: page
title: Game Boy Color Emulator
description: A GBC emulator written from scratch in Rust, focusing on hardware-level accuracy and memory architecture.
img: assets/img/gameboy-emulator.png
importance: 2
category: Rust
date: 2025-10-15
tags: ["Rust", "Hobby", "GameDev"]
github: https://github.com/chalune-dev/gameboy
---

A Game Boy Color emulator built in Rust mainly over a weekend with a group of friends, the same team that worked on the Minecraft clone project.

My background in engineering and embedded systems provided a strong foundation for this project, allowing me to take on a heavy role in the low-level architectural design. Because I already had hands-on experience with hardware architecture and assembly, I focused on accurately recreating the console's internal behavior.

My main technical contributions included:

- **Memory Architecture:** Help in designing the general memory layout and implementing the memory bus to ensure accurate read/write routing.
- **CPU & Assembly:** Building out the logic to correctly parse and execute the Game Boy's custom assembly instruction set.
- **Hardware Timers:** Implementing the generation of the internal system timers required to keep the emulator's hardware components strictly synced.
