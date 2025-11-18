# DSC212 ASSISGNMENT IMS24074
_ _ _ _
# DSC212: Spectral Modularity on the Karate Club Graph

This repository contains the solution for the DSC212: Graph Theory research assignment.

The project implements a recursive spectral partitioning algorithm to find and analyze community structures in **Zachary's Karate Club graph**.

## Key Features

This notebook successfully completes all required assignment tasks:

* **Recursive Spectral Partitioning:** A core function that recursively splits the graph into communities based on the eigenvectors of the modularity matrix.
* **Step-by-Step Visualizations:** The graph is plotted after each split, showing the newly formed communities in different colors while maintaining a fixed layout.
* **Node Metrics:** At each iteration, four key metrics are calculated for all nodes:
    * Degree Centrality
    * Betweenness Centrality
    * Closeness Centrality
    * Clustering Coefficient
* **Metric Evolution Plots:** Line charts show how these metrics evolve for each node (with nodes 0 and 33 highlighted) as the communities are divided.
* **Final Discussion:** A written analysis is included in the notebook, discussing which nodes remain central and how the community structure influences the metrics.

## How to Run

1.  Clone this repository.
2.  Open the `DSC212_ASSIGNMENT_IMS24074.ipynb` file in a compatible environment (like Google Colab, VS Code, or Jupyter Lab).
3.  Run the cells from top to bottom. The notebook is designed to run sequentially without any manual edits.

## Libraries Used

* `networkx`
* `numpy`
* `matplotlib` & `seaborn`
* `pandas`
* `scipy`
