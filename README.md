# Sand-Lab
A particle simulation system built in Python, showcasing behaviors of sand-like particles within a dynamic grid. Inspired by cellular automata and particle physics, this project simulates how granular materials interact with their environment, offering a visually captivating experience through a custom-rendered canvas. The system is built to be both efficient and highly customizable, allowing users to explore complex particle dynamics in real-time.

## Key Features:
Particle Physics Simulation: Realistic simulation of granular particles, each interacting with gravity and neighboring particles within a grid-based environment.
Interactive Visualization: Users can directly manipulate the simulation by interacting with a visual canvas, drawing, and adjusting particle distributions.
Efficient Grid Management: Optimized algorithms ensure that the grid structure updates fluidly, enabling a smooth simulation even with large numbers of particles.
Customizable Parameters: Adjust simulation parameters such as gravity, particle density, and interaction rules to experiment with different environments and behaviors.

## How It Works:
At its core, the Sand-Lab revolves around three primary components:

1. sand.py
This is the heart of the simulation. It controls particle behavior based on defined rules for movement, interaction, and environmental influence (e.g., gravity). The particles in the simulation respond dynamically to both user input and environmental changes, producing visually stunning patterns and behaviors.

2. drawcanvas.py
The canvas is where the simulation comes to life. This file handles rendering the grid and particles, managing the graphical interface and user interaction. Users can add particles, clear the grid, and watch the simulation evolve over time, providing an immersive experience.

3. grid.py
The grid manages the structure of the environment, maintaining the position and status of each particle. It also efficiently calculates how particles interact with one another, allowing for smooth transitions and updates during the simulation.

## Interaction and Customization:
The user can modify various parameters, such as:

Gravity strength: Alters how strongly particles are pulled downward.
Particle interaction rules: Adjust the behaviors of particles when they collide or interact.
Canvas size and resolution: Customize the grid and display size for different performance needs or visual preferences.
This modular approach to building the project makes it easy to extend or enhance, whether adding new types of particles or altering existing interaction dynamics.
