# Nerf-Football-DFBI-Full-6-Degrees-of-Freedom

A 6 degrees of freedom (6-DOF) simulation using Dynamic Fluid Body Interaction (DFBI) methodology for analyzing a Nerf football's motion in fluid environments.

## Overview

This simulation captures the motion of a rigid body subject to fluid forces, tracking both translational and rotational dynamics across all six degrees of freedom:
- **Translation**: X, Y, Z displacement
- **Rotation**: Roll, Pitch, Yaw angular velocities

## Results

### Mesh Visualization
![Computational Mesh](Mesh.png)
*Computational domain and mesh used for the simulation*

### Coefficient of Drag
![Drag Coefficient](CD.png)
*Time history of drag coefficient showing flow development*

### Translational Motion
![Translation Velocity](TranslationVelocity.png)
*Translational velocity components over time*

### Rotational Motion
| X-Angular Velocity | Y-Angular Velocity | Z-Angular Velocity |
|:--:|:--:|:--:|
| ![X Angular Velocity](XangularVelocity.png) | ![Y Angular Velocity](YangularVelocity.png) | ![Z Angular Velocity](ZangularVelocity.png) |
*Angular velocity components showing rotational dynamics*

### Animation
![Simulation Animation](NerforNothing.gif)
*Complete 6-DOF motion visualization*

## Simulation Details

### Methodology
- **Solver**: DFBI (Dynamic Fluid Body Interaction)
- **Degrees of Freedom**: 6 (3 translational + 3 rotational)
- **Coupling**: Fluid-structure interaction with rigid body dynamics

### Key Features
- Real-time fluid force computation
- Coupled translation and rotation dynamics
- Comprehensive motion tracking
- Visualization of all motion components


