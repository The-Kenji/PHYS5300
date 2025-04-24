In this project, I explore the chaotic motion of a two-dimensional, incompressible, and inviscid external flow past a thin flat plate using Python. The models are optimized to run efficiently on a Jupyter Notebook. I implement two distinct approaches:
- Euler/Lattice Boltzmann Method (LBM):
This popular approach leverages the Euler form of the Navier–Stokes equations combined with the Lattice Boltzmann Method to model the flow.
- Lagrangian-based Smooth Particle Hydrodynamics (SPH):
This method represents the fluid with moving particles to simulate the flow dynamics.

Both simulations provide interactive visualizations equipped with widgets that allow users to define the plate’s angle of attack. Additionally, they display the time evolution of key flow quantities—lift force, mass flow rate, momentum, and total kinetic energy—so that vortex shedding and unsteady lift behavior become readily observable.
For simplicity, both simulations use a basic Euler-based integration scheme. Although I experimented with higher-order solvers for the Lagrangian SPH model, the increased computational cost outweighed the marginal benefits in accuracy.


