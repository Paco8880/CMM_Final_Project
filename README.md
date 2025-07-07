# CMM_Final_Project
## Economic Behavior Diffusion Simulation

This project simulates how economic behaviors (like adopting a new product or technology) spread through social networks. We explore how network structure and individual thresholds affect the diffusion process.

## Motivation

This project is based on the concept of **complex contagion**, as explored by Damon Centola (2021) and others. Unlike simple contagions (like viruses), complex behaviors, such as adopting an innovation or changing economic habits, often require multiple exposures from peers before someone decides to adopt.

## Simulation

We simulated the spread of economic behavior across different types of networks and under varying individual adoption thresholds. Our goal was to understand how network structure and threshold diversity influence the dynamics of diffusion.

- It compares clustered (Watts–Strogatz) vs. random (Erdős–Rényi) networks.
- It shows how diversity in individual adoption thresholds leads to larger cascades.
- It analyzes how the final adoption rate depends on seed size and threshold level.

## Requirements

- Python 3.10+
- NetworkX
- NumPy
- Matplotlib
- Seaborn
- Mesa
