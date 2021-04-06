# fenics-problems
Archived work on solving various partial differential equations using [FEniCS](https://fenicsproject.org/) Python package as part of my undergraduate research with Dr. Ulisses Braga-Neto.

## Introduction
Some equations in the real world can't just be solved. If you wanted to predict or model:
+ tomorrow's weather outlook
+ performance of a particular airfoil design
+ electromagnetic scattering or waveguides
+ the pumping of blood through a human heart
+ or really any problem involving partial differential equations

Then Finite Element Analysis might be the tool for the job. In a nutshell, the process goes like this:
1. Pose the problem in a variational formulation
2. Discretize the domain
3. Apply an optimization strategy

## Examples
### Burgers Equation

![burgers](https://user-images.githubusercontent.com/57698676/113661063-09804380-966b-11eb-8a1c-092e647f168d.png)

The resulting evolution can be used for applications in fluid mechanics, nonlinear acoustics, gas dynamics, and traffic flow[*](https://en.wikipedia.org/wiki/Burgers%27_equation).

[![Burgers' Equation](https://img.youtube.com/vi/zsyWq-99fFA/0.jpg)](https://www.youtube.com/watch?v=zsyWq-99fFA)

### Allen-Cahn Equation
A similar framework can be applied to the Allen-Cahn Equation:
[![Allen-Cahn Equation](https://img.youtube.com/vi/-rGxXzTWw9g/0.jpg)](https://www.youtube.com/watch?v=-rGxXzTWw9g)

### Cahn-Hilliard Equation
As well as the Cahn-Hilliard Equation, which uses two separate equations coupled together in adjacent vector spaces.
[![Cahn-Hilliard Equation](https://img.youtube.com/vi/oma4NlOp4C4/0.jpg)](https://www.youtube.com/watch?v=oma4NlOp4C4)
