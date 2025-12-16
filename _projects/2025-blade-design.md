---
layout: project
title: Wind Turbine Blade Design
description: Design and Prototype Project
technologies: [Autodesk Fusion, MATLAB]
image: /assets/images/Blade_Renders.jpg #replace
---

Our team set out to design, build, and test small-scale wind turbine blades optimized for maximum power output in a controlled wind tunnel environment. The project required balancing aerodynamic efficiency with strict geometric and material constraints: a maximum blade radius of 6 inches, chord length under 2 inches, and allowable stress below 58 MPa. We selected a target operating speed of 1200 RPM, scaled to reflect the small turbine size, and used the Betz-limit blade element momentum theory as the foundation for our optimization.

The design process began with MATLAB-based modeling, where we generated chord, pitch, and twist distributions along the blade span. We chose the NACA 6412 airfoil for its high lift-to-drag ratio and suitability for low-speed conditions. Structural analysis confirmed that the blades would withstand expected forces, with calculated bending stresses well below the material threshold. This gave us confidence to move forward with fabrication and testing.

Performance assessment was carried out in the wind tunnel using a LabVIEW-controlled data acquisition system. We collected torque and RPM data across a range of wind speeds and generated power curves to compare experimental results with theoretical predictions. While the blades met all structural and geometric constraints, the experimental power output (0.048 W) fell short of the theoretical value (1.528 W). This highlighted inefficiencies due to mechanical losses, aerodynamic limitations, and non-ideal system behavior.

Despite the performance gap, the project demonstrated several successes: the blades remained structurally sound throughout testing, data collection was consistent, and our methodology provided a clear framework for iterative improvement. In reflecting on the process, we identified opportunities for refinement, including incorporating more realistic induction factor modeling, optimizing for torque as well as power, and expanding measurement points for smoother performance curves.

Beyond the technical outcomes, the project emphasized collaboration and problem-solving. Our group worked cohesively, troubleshooting challenges as they arose and maintaining a strong team dynamic. The experience reinforced the importance of bridging theoretical modeling with experimental validation, and it provided valuable insight into the complexities of translating aerodynamic theory into practical design.
