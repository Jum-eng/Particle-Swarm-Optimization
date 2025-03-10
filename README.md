# Particle-Swarm-Optimization
Overview
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
