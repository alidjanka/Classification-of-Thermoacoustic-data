# Classification-of-Thermoacoustic-data

This notebook implements a simple feedforward neural network that can solve a classification problem.

The dataset comes from a stability analysis of a thermoacoustic system whose stability depends on the "flame delay" (the time it takes for a flame to react to an upstream velocity perturbation) and the downstream reflection coefficient.
The objective is to develop a classifier that can appropriately find the boundary between the blue and red dots given some pair of inputs x.
