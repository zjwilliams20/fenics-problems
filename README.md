# fenics-problems
Archived work on solving various partial differential equations using [FEniCS](https://fenicsproject.org/) Python package as part of my undergraduate research with Dr. Ulisses Braga-Neto.

## Introduction
Some equations in the real world can't just be solved. If you wanted to predict or model:
+ tomorrow's weather outlook
+ performance of a particular airfoil design
+ electromagnetic scattering or waveguides
+ the pumping of blood through a human heart
...or really any problem involving partial differential equations, then Finite Element Analysis might be the tool for the job.

In a nutshell, the process goes like this:
1. Pose the problem in a variational formulation
2. Discretize the domain
3. Apply an optimization strategy

As an example, consider the Burgers Equation.
