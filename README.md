# 2D Lattice-Based Structure

The provided Python code simulates the dynamic behavior of a structural system with a central hole or edge crack using a spring-node model. The structure consists of interconnected nodes, representing physical points in the system, connected by springs. The simulation captures the movement and interaction of these nodes under the influence of springs and a central hole or edge crack. The defect has a zero spring constant, affecting the behavior of the connected nodes. The simulation progresses over multiple steps, and the results are visualized, showing the dynamic response of the structure to applied forces and the presence of the central hole or edge crack. The code allows for the customization of various parameters, such as the number of nodes, spring constants, and critical stretch thresholds, providing flexibility for experimenting with different structural configurations. Overall, this simulation serves as an illustrative example of how a simple spring-node model can represent the dynamic behavior of a structural system with defects.

## Features

- **Dynamic Simulation**: The code dynamically simulates the behavior of the structure over a specified number of steps.
- **Visualization**: Utilizes matplotlib to visualize the nodes, springs, and the progression of the simulation.
- **Central Hole Representation**: Introduces a central hole with zero spring constant, showcasing its influence on the overall system.
- **Edge crack Representation**: Introduces an edge crack with zero spring constant, showcasing its influence on the overall system.

## Configuration

- `NUM_NODES_X` and `NUM_NODES_Y`: Adjust the number of nodes in the X and Y directions.
- `SPRING_CONSTANT`: Set the spring constant for regular springs.
- `DISPLACEMENT_RATE`: Define the constant rate of displacement for the top row nodes.
- `CRITICAL_STRETCH`: Set the critical stretch threshold for springs to break.
- `DAMPING_COEFFICIENT`: Define the damping coefficient for regular springs.

# Central Hole Structure Simulation

## Results
![Central-Hole](https://github.com/Hossein-Talebi1375/Lattice-Based-Structure/assets/153290352/0a595fa7-8a8f-41e4-b550-6ea1a6529c33)


# Edge Crack Structure Simulation

## Results
![Edge-Crack](https://github.com/Hossein-Talebi1375/Lattice-Based-Structure/assets/153290352/acaf5e9d-e677-47a8-a236-f6dd2cc3aafc)

## Customization

Feel free to experiment with different parameters, initial conditions, or structural configurations by modifying the code.


