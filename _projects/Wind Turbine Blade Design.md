---
layout: project
title: Turbine Blade Design
description: Class project designing small scale wind turbine blade
technologies: [MATLAB, Fusion360]
image: /assets/images/cad-screenshot.png
---


## Overview
As part of the MAE 4272 course this project focused on the design, fabrication, and experimental testing of a small-scale wind turbine optimized for power production at a chosen angular velocity. Wind velocity was assumed to follow a given Weibull probability distribution. The goal of this design was to maximize aerodynamic efficiency while satisfying strict geometric, structural, and operational constraints imposed by lab equipment.

## Design Process
Our blade design was a blend of two airfoils. We chose to combine NACA 4412 at the root and NACA 6409 near the tip. We did this by using nine cross sections in total, with four cross sections of NACA 4412 that smoothly transitioned into five cross sections of NACA 6409 spanning across the blade from root to tip, respectively. A MATLAB script was created to automate calculations for our nine blade elements. This script was used to calculate forces and optimal chord lengths for the blade. 

![Screenshot of cad file]("/assets/images/cad-screenshot.png")

## Testing Summary
![Picture of testing setup]("/assets/images/testing-pic.png")

To test our blades we ran a series of tests that studied the power output at specific wind velocities within the given Weibull distribution. At each wind velocity, the torque applied to the turbine shaft was incrementally increased until equilibrium was reached. This was done to simulate power output, since our experimental turbine setup was not actually connected to a gearbox. With this data, we were able to graph power curves and study the efficiency of the blades. This allowed us to confirm whether or not our design behaved as expected.

### Graph showing power curves collected during testing phase:
![Graph showing power curves.]("/assets/images/power-curves.png")

### Chart showing calculated efficiencies:
![Graph showing efficiency.]("/assets/images/efficiency.png")

If we were able to complete a second iteration of our design, we would have made changes to improve these efficiencies. 

## Contributions
As a part of the design team, I contributed to the airfoil selection and testing procedure. I researched airfoil classifications and chose two cross sections to combine for our blade design. This was a large part of our design process, and allowed us to optimize the blade efficiency. Testing involved attaching our blades to a given hub and axis setup in the course lab. We ran several tests at different velocities to asess the power output of our turbine. I was the team member to choose what velocities we would test and I controlled the wind tunnel during this procedure, ensuring safe operating conditions and quality data collection. 



