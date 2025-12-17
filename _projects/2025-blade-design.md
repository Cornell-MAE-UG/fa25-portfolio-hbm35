---
layout: project
title: Wind Turbine Blade Design
description: Design and Prototype Project
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/Blade_Renders.jpg #replace
---

Project Overview
As part of MAE 4272, our team was tasked with designing, fabricating, and testing small‑scale wind turbine blades optimized for maximum power output in a controlled wind tunnel environment. The challenge required balancing aerodynamic efficiency with strict geometric and material constraints: a maximum blade radius of 6 inches, chord length under 2 inches, and allowable stress below 58 MPa. This project provided an opportunity to connect aerodynamic theory with practical engineering design.

Design Process
We selected a target operating speed of 1200 RPM, scaled to reflect the turbine’s size, and applied blade element momentum theory with the Betz limit as the foundation for optimization. Using MATLAB, we generated chord, pitch, and twist distributions along the blade span. After evaluating airfoil options, we chose the NACA 6412 for its high lift‑to‑drag ratio and suitability for low‑speed conditions. Structural analysis confirmed that the blades would withstand expected forces, with bending stresses well below the material threshold, giving us confidence to proceed with fabrication and testing.

Testing Summary
Performance assessment was conducted in the wind tunnel using a LabVIEW‑controlled data acquisition system. Torque and RPM data were collected across a range of wind speeds, and power curves were generated to compare experimental results with theoretical predictions. While the blades met all structural and geometric constraints, the measured power output (0.048 W) fell short of the theoretical value (1.528 W), highlighting inefficiencies due to mechanical losses, aerodynamic limitations, and non‑ideal system behavior. Despite this gap, the blades remained structurally sound, and the testing framework provided valuable insights for iterative improvement.

Power curves generated:
![Power Curve]({{ site.baseurl }}/assets/images/power-curve.jpg)

My Contribution
I focused on crafting the testing protocol to standardize wind tunnel procedures and the analysis and reflection on performance outcomes. Additionally, I structured the presentation and final report, ensuring our findings were communicated clearly and professionally. These contributions helped translate technical results into a cohesive narrative suitable for both academic and professional audiences.
