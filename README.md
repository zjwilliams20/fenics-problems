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

![](https://github.com/zjwilliams20/fenics-problems/blob/main/media/burgers.png)

Our goal here would be to understand the evolution of Equation 1 over the domain -1 to 1, for one second, subject to the initial conditions specified by Equation 2, and the boundary conditions from Equation 3.

The resulting evolution can be used for applications in fluid mechanics, nonlinear acoustics, gas dynamics, and traffic flow[*](https://en.wikipedia.org/wiki/Burgers%27_equation).

[![](https://img.youtube.com/vi/oma4NlOp4C4/0.jpg)](https://www.youtube.com/watch?v=oma4NlOp4C4)
