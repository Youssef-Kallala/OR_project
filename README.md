# Hamiltonian Path Algorithms: A Comparative Analysis

This project explores and implements two different algorithms for solving the Hamiltonian Path problem, a classic challenge in graph theory and operations research.

## Project Overview

The goal of this project is to find a path in a directed or undirected graph that visits each vertex exactly once. Two main approaches are implemented in the `ProjetROimplementation.ipynb` notebook:

1.  **Dynamic Programming Approach**: A classic, exact algorithm that uses bitmasking to explore all possible paths. It is guaranteed to find a solution if one exists but has an exponential time complexity of O(2^n * n^2).
2.  **Randomized Algorithm with Link-Cut Trees**: A more advanced, probabilistic approach that uses a sophisticated Link-Cut Tree data structure. This method is much faster for larger graphs but is not guaranteed to find a path in every run.

## How to Run This Project

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/Youssef-Kallala/OR_project.git
    cd OR_project
    ```

2.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Launch Jupyter Notebook and open the file:**
    ```bash
    jupyter notebook ProjetROimplementation.ipynb
    ```

## Dependencies
- networkx
- matplotlib
- pyvis
