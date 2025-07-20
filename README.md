# Reproducibility Materials for "International Conference on Service-Oriented Computing, 2025"

This repository contains the codes necessary to reproduce the results presented in our anonymous submission to ICSOC, 2025.

## Contents

The first cell of each notebook provides a description and instructions for executing the notebook. The repository is organized into the following Jupyter notebooks and datasets:

### Notebooks

- **`Skyway Network Dataset.ipynb`**  
  This notebook crawls raw data from the OpenStreetMap website and generates a skyway network for drone delivery operations used in our experiments. The generated skyway network consists of 59 nodes and 1210 Line-of-Sight (LoS)-based skyway segments. 

- **`Drone Delivery Flights Dataset.ipynb`**  
  This notebook generates the drone delivery flights dataset used in the experiments. 

- **`Fairness-based Intervention.ipynb`**  
  Evaluates an alternative approach that prioritizes drones using a fairness-based approach to provision the charging needs of drones. 

- **`Greedy Intervention.ipynb`**  
  Evaluates an alternative approach that greedily allocates charging resources to drones with the least recharging needs to maximize pad turnaround. 

- **`Proposed Intervention.ipynb`**  
  Implements our proposed heuristic-driven strategy designed to optimize the QoS fulfillment of drone services.

- **`Results.ipynb`**  
  Analyzes and compares the performance of the above approaches under varying drone traffic loads.  
Plots the results for comparative analysis in terms of efficiency and effectiveness.

## Instructions

To reproduce our results:

1. Clone this repository.
2. Run the notebooks in the order listed above using Jupyter Notebook or JupyterLab.
3. Ensure you have the required Python libraries installed:
   - `pandas`
   - `numpy`
   - `matplotlib` etc.

> **Note:** All notebooks are self-contained. The first cell in each notebook provides a description of its purpose and instructions for execution.

## Anonymity Note

This repository has been anonymized in compliance with double-blind review guidelines. Identifying information has been removed.
