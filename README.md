# Nematode Navigation Simulator

## Overview
This project simulates a nematode (worm) navigating a grid to find food using gradient-based decision-making. It includes a simulation environment, a heuristic controller for decision-making based on local gradients, and a neural network trained to predict movement directions for optimized navigation.

## Features
- **Simulation Environment**: Simulates a grid where a worm navigates to find food pellets.
- **Heuristic Controller**: Determines the worm's move based on the highest local gradient, simulating chemotaxis.
- **Worm Environment Manager**: Manages grid, worm, and food pellets, including their positions and updating the environment.
- **Neural Network Controller**: Uses generated training data to learn optimal movement strategies through supervised learning.

## Visualization
The project includes functionality to visualize the worm's movement and the environment's state using `matplotlib`, with real-time updates as the simulation progresses.
