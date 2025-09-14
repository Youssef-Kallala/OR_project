# Vehicle Routing Problem: A Heuristic Approach

This project explores a heuristic solution for the classic Vehicle Routing Problem (VRP), a well-known challenge in logistics and operations research.

## Project Overview

The goal of this project is to find the optimal set of routes for a fleet of vehicles to serve a given set of customers. The implementation is contained in the `HeuristicApproach.ipynb` Jupyter Notebook.

The approach taken is a clustering-based heuristic:
1.  **Clustering**: Customers are grouped into clusters using the K-Means algorithm from `scikit-learn`.
2.  **Routing**: For each cluster, a simple path is determined, starting and ending at the depot.
3.  **Visualization**: The final clusters and routes are visualized using `matplotlib` and `seaborn`.

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
    jupyter notebook HeuristicApproach.ipynb
    ```

## Dependencies

The project relies on the following Python libraries, as listed in the `requirements.txt` file:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
