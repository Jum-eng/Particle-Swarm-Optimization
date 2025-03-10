# Particle-Swarm-Optimization

This project demonstrates Particle Swarm Optimization (PSO), an optimization algorithm inspired by the swarming behavior of birds and fish. The visualization shows how particles explore the search space and converge towards an optimal solution over time.

## How PSO Works
PSO is a population-based optimization technique where particles adjust their positions based on:
Their own best-known position (personal best – pbest).
The best-known position found by the swarm (global best – gbest).
Each particle's movement is influenced by inertia, personal experience, and social learning from the swarm. The algorithm iteratively updates particle velocities and positions to minimize the given objective function.

## Objective Function
The optimization is performed on a function that combines quadratic terms with sinusoidal components, making it a challenging landscape for optimization. The goal is to find the function's global minimum.

## Visualization
The search space is represented as a contour plot.
Particles are plotted as moving points that update their positions at each iteration.
The true global minimum is marked to compare PSO’s performance.
The animation illustrates how particles adjust their positions over multiple iterations.

## Algorithm Steps
Initialize particles with random positions and velocities.
Evaluate the function value at each particle’s position.
Update personal bests (pbest) for each particle.
Determine global best (gbest) based on the best function value found.
Adjust velocities based on inertia, personal best, and global best.
Update positions of particles.
Repeat the process until convergence or a set number of iterations is reached.

## Expected Outcome
The particles should gradually converge towards the global minimum.
Over iterations, the swarm refines its search, balancing exploration (searching new areas) and exploitation (refining known good solutions).
The final solution found by PSO is compared to the actual global minimum.
How to Run the Project
Install necessary dependencies such as NumPy and Matplotlib.
Run the script to execute the PSO algorithm.
Observe the animation of particles converging toward the optimal solution.

## Conclusion
This project provides an intuitive understanding of PSO through a dynamic visualization. It showcases how the algorithm iteratively improves solutions and adapts based on swarm intelligence principles.







