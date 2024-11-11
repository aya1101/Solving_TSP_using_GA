# Solving_TSP_using_GA

## Overview
This project aims to solve the Traveling Salesman Problem (TSP) using a Genetic Algorithm (GA). The TSP is a well-known optimization problem where the goal is to find the shortest possible route that visits each city exactly once and returns to the starting city. Genetic algorithms are a type of evolutionary algorithm that can approximate solutions to optimization and search problems, making them well-suited for solving TSP.

## Algorithm
The Genetic Algorithm for TSP includes the following main steps:
1. **Initialization**: Generate an initial population of possible routes.
2. **Selection**: Select the fittest individuals (routes) from the population.
3. **Crossover**: Combine pairs of routes to produce new offspring routes.
4. **Mutation**: Randomly modify some routes to maintain diversity.
5. **Replacement**: Replace the least fit routes with new offspring.
6. **Termination**: The algorithm stops when a set number of generations is reached or a satisfactory solution is found.

## Installation
To run this project, you'll need Python and the following libraries:
- `numpy`
- `matplotlib`

You can install the dependencies with:
```bash
pip install -r requirements.txt
