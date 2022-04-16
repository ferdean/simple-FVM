# Simple FVM solver

This is the project for the exam of the course Scientific Computing at TU Berlin (WiSe 2021/2022), developed by F. Sindy, V. Yelnyk and F. de Andres and delivered to J. Fuhrmann.

The current code solves a system of Darcy's equation for flow in a porous medium saturated with water and convective heat equation. In addition to the simple formulations in the SciComp lectures, we include two additional effects: 

* Heat expansion leading to a decrease of the water density and therefore a tendency for less dense (lighter) water to move up in the force field of gravity. 
* Convective heat transport: heat not only moves due to heat conduction, but also along with the moving water
