# FreeCAD-FEM-examples
FreeCAD FEM examples using Elmer backend

Requirements: 
- FreeCAD 0.21.1
- ElmerSolver 9.0 (Rev: c82f31df0 is tested and it works)
- GMSH 4.10

## fem-elmer-tube-thermalflow-velocity-3d
This model simulates water flows heat sink. The model uses heat transfer and Stokes-Navier equations and calculates temperature, velocity and pressure fields.
![pressure](https://user-images.githubusercontent.com/99616450/215445951-1a98be62-e34a-4090-8fcc-8b678e370ff2.png)

## full-bridge_on_radiator
This model simulates heating of a radiator with four transistors in TO-220 cases. Power dissipation of the transistors: 3.04 W, 1.91 W, 4 W and 0 W. Petals of radiator are surrounded air flow with velocity 0.05 m/s. The model uses heat transfer and Stokes-Navier equations. The model doesn't use radiation equations because of FreeCAD doesn't support them yet (but Elmer supports). So the temperature in the model higher than in experiment.
![screen](https://github.com/mist90/FreeCAD-FEM-examples/assets/99616450/00cdc676-aab9-4d6f-9d97-baf68f058655)
