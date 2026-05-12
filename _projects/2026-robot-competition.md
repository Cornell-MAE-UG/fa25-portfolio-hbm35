---
layout: project
title: Mechatronics Robot Competition
description: Design and Prototype Project
technologies: [Arduino IDE, CAD, TinkerCAD]
image: /assets/images/Bot-1.jpg #replace
---

## Project Overview

Our team designed, built, and programmed an autonomous competition robot for the Cube Craze challenge in my mechatronics course, following strict constraints on size, power, and real‑time C‑based control. Through my group of 3, we went through a full iteration of prototyping including strategizing, mechanical design, sensor integration, and embedded programming. Following the class structure, we worked within a structured time-dependent milestone system to progressively build a competition‑ready robot. The milestones consisted of an initial design pitch, a mobility challenge, a color sensing integration, and a cube clearing process. Within our team, we used iterative prototyping and testing to refine both hardware and software. 

## Design Process

For specifics on the design, we implemented all motor control using direct register manipulation on the Arduino UNO, with no Arduino functions allowed, developing a deep understanding of H‑bridge control, timing, and movement calibration. We then built an interrupt‑driven color‑sensing system to measure sensor output frequency and classify yellow, blue, and black surfaces in real time. Then using milestone 3, we built upon the previous code and developed a reliable navigation system that allowed the robot to detect its starting color, reverse direction at boundaries, and avoid leaving the board. For the mechanical aspect, we designed and tuned a collection strategy, including funneling features to gather the cubes into our robot.

## Testing Summary

In this deadline-driven project, we successfully completed all milestones on time, contributing to strong competition seeding and a fully autonomous final robot. In the competition, our robot demonstrated consistent cube‑clearing performance within the one‑minute match window, meeting the competition requirement of gathering more cubes than the opponent. Through this project, I gained hands-on experience with embedded systems, real‑time programming, mechanical prototyping, and team‑based engineering workflows. I was able to strengthen my skills in debugging, rapid iteration, and designing under constraints and develop a deeper appreciation for the integration of hardware and software in autonomous systems.

Rendered blades: 
<img src="{{ site.baseurl }}/assets/images/Bot-1.jpg" alt="Blades" width="500">