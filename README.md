# CMPG 313 – K-Means Clustering of Dense Network Topology




* Module: CMPG 313 – Artificial Intelligence



## Project Overview

This project explores the application of the **K-Means clustering algorithm** on a dense network topology consisting of over 600 interconnected nodes. Each node is assigned spatial coordinates (X, Y) and an energy value to simulate real-world systems such as wireless sensor networks or IoT environments.

The goal is to analyse how clustering behaves in dense and overlapping data environments, and to evaluate the relationship between clusters and energy distribution.



##  Technologies Used

* Python 3
* NumPy
* Pandas
* Matplotlib
* NetworkX
* Scikit-learn
* SciPy



## How to Run the Project

1. Ensure Python 3 is installed
2. Install required libraries:

```bash
pip3 install numpy pandas matplotlib networkx scikit-learn scipy
```

3. Run the script:

```bash
python3 kmeans.py
```



##  Experiment Description

The experiment was conducted in two phases:

###  Phase 1: Default Clustering (k = 7)

* The network was clustered into 7 groups
* Clusters were more detailed and localized
* Better separation between dense communities

###  Phase 2: Modified Clustering (k = 3)

* The number of clusters was reduced to 3
* Clusters became larger and more generalized
* Some communities merged into broader groups


##  Results & Observations

##Cluster Behaviour

* With **k = 7**, clusters are more precise and reflect the underlying network structure
* With **k = 3**, clusters are broader and less distinct
* Reduction in k results in loss of fine detail




## Screenshots

Screenshots of the following were captured and included in this repository:

* Terminal execution (k = 7 and k = 3)
* 2D clustered network graph
* 3D clustered scatter plot
* 3D energy surface plot



