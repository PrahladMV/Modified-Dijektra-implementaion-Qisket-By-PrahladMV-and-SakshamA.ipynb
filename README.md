# Modified-Djektra-Implementaion-Qisket-by-Prahlad.M.V-and-Saksham.A.ipynb
# Quantum Implementation of the Modified Dijkstra's Routing Algorithm

## Overview
This repository contains the quantum implementation of the **Modified Dijkstra's Routing Algorithm** using **Qiskit**. The project demonstrates how quantum computing techniques can be applied to enhance traditional algorithms like Dijkstra's algorithm, which is widely used for finding the shortest paths in weighted graphs.

## Project Description
The **Modified Dijkstra’s Algorithm** is a modification of the classical Dijkstra's algorithm, incorporating quantum computing concepts. In this project, we utilize quantum circuits to perform the routing algorithm more efficiently by exploiting quantum parallelism.

### Key Features:
- Quantum-based implementation of Dijkstra's algorithm.
- Developed using **Qiskit** for quantum circuit simulations.
- Offers insights into how quantum computing can be integrated into graph theory problems.

## Requirements
Before running the project, ensure you have the following dependencies installed:

- **Python 3.10** or above.
- **Qiskit**: Version 0.43.1 or above.
- **Qiskit-Aer**: Version 0.12.0 or above.
- **Qiskit-Terra**: Version 0.24.1 or above.
- **Jupyter Notebook** or any other Python environment to execute the code.

### Installing Dependencies:
You can install the necessary dependencies using the following commands:

bash
pip install qiskit==0.43.1
pip install qiskit-aer==0.12.0
pip install qiskit-terra==0.24.1

### How to Run:
1. **Clone the repository.**
git clone https://github.com/<your_username>/modified-dijkstra-quantum.git
cd modified-dijkstra-quantum
2. **Open the Jupyter Notebook file** modified_dijkstra_implementation_qiskit_by_prahlad_and_saksham.ipynb
3. **Run the notebook step by step, ensuring each quantum circuit is correctly simulated and the routing algorithm is executed as intended**.

### Algorithm Flow
1. **Graph Representation**: The graph is represented as an adjacency matrix, where the elements represent the weights between nodes.
2. **Quantum Circuit**: A quantum circuit is built to handle the pathfinding process, leveraging quantum operations to find the optimal path faster than classical algorithms.
3. **Modified Dijkstra’s Algorithm**: The classical Dijkstra’s algorithm is modified to utilize quantum computation in the weight comparison steps, enabling a potentially faster solution in large graphs.

### Results
After running the algorithm, you will get the shortest path and its corresponding weight between the nodes in the graph. The quantum version leverages quantum gates to perform certain operations in parallel, potentially reducing time complexity.

### License
This project is licensed under the MIT License - see the LICENSE.md file for details.

### Contributing
We welcome contributions! Feel free to fork the project and submit a pull request. For any issues or feature requests, please open an issue. This modified version of the algorithm was implemented by Prahlad MV and Saksham A, building upon the work of Robert Botez, whose earlier implementation utilized previous versions of Qiskit.

You can copy all of the above and paste it directly into your **README.md** file. Let me know if you need further changes!
