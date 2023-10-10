# Collaboration-Matrix-Analyzing-Visualizing-the-Scientific-Collaboration-Landscape


## Overview
"Collaboration Matrix" is an engaging exploration into a network depicting scientific collaborations among research authors. The project illuminates the intricate landscape of academic partnerships, providing a detailed analysis and visualization of network structures, robustness, community formations, and dynamic behaviors within the collaboration network.


## Tasks
The project meticulously addresses the following pivotal tasks:
1. **Network Initialization & Preprocessing**: Embarks with loading and preprocessing the network data to ensure accurate representation and readiness for subsequent analysis.
2. **Robustness Against Random Failures**: Evaluates and compares the network's robustness against random failures with its randomized counterpart.
3. **Community Detection & Analysis**: Implements the Girvan-Newman algorithm for insightful community detection and analysis within the network.
4. **Disease Propagation Simulation**: Executes and analyzes the SIRS model to simulate disease spread across identified communities, studying various initial conditions and their implications.
5. **Unique Failure Propagation Model Analysis**: Introduces and scrutinizes a distinctive failure propagation model, examining the avalanche sizes distribution and assessing network robustness and model sensibility.

## Dataset
The dataset underpinning this project is a representation of scientific collaborations:
- `netscience.mtx`: A matrix file containing the network's edges, signifying collaborations between different nodes.

## Results
The project yielded significant insights into the network's structural and dynamic characteristics:
- **Robustness Analysis**: The network displayed vulnerability to targeted attacks while maintaining relative robustness against random failures.
- **Community Structure**: Identified distinct communities within the network, each varying in size and connectivity, revealing the network's modular structure.
- **Disease Propagation**: Simulation of disease spread within identified communities showcased different dynamics based on community sizes and initial infection points.
- **Failure Propagation Model**: Introduced a novel failure propagation model, revealing that the network is not robust against cascading failures initiated by single-node failures.

## Technologies and Libraries
- Python
- NetworkX
- Matplotlib
- NumPy

## Visuals

https://github.com/aminfa576/Collaboration-Matrix-Analyzing-Visualizing-the-Scientific-Collaboration-Landscape/blob/374ffaf1f8b6d43ab6d3c1d26535c853ed9c7a59/Disease%20Propagation%20Simulation.png


## Conclusion
"Collaboration Matrix" is a deep and insightful exploration into the world of scientific collaboration networks. Through a series of analytical tasks and simulations, the project unveils the structural and dynamic nuances of academic partnerships. Its findings and insights are indispensable for individuals and entities engaged in network science, graph theory, and related disciplines.


