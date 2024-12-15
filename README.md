# K-Means Clustering Algorithm in Python

This project demonstrates an implementation of the **K-Means clustering algorithm** using Python. The algorithm clusters a dataset into \( k \) distinct groups based on feature similarity. It includes:

- Initialization of cluster centers.
- Iterative optimization of assignments (Expectation step).
- Update of cluster centers (Maximization step).
- Visualization of the clustering results.

---

## Features

1. **Custom Implementation of K-Means**:
   - Functions:
     - `findMapping`: Assigns data points to the nearest cluster.
     - `findMeans`: Computes new cluster centers.
     - `kmeans`: Integrates the above functions to implement the full K-Means algorithm.

2. **Visualization**:
   - The final clustering results are visualized using `matplotlib`, displaying:
     - Data points color-coded by cluster.
     - Red markers for cluster centers.

---

## Requirements

This project requires the following Python libraries:

- `numpy`: For numerical operations.
- `matplotlib`: For plotting results.
- `scikit-learn`: Used for generating synthetic datasets.

Install these using:

```bash
pip install numpy matplotlib scikit-learn


## Features

1. **Custom Implementation of K-Means**:
   - Functions:
     - `findMapping`: Assigns data points to the nearest cluster.
     - `findMeans`: Computes new cluster centers.
     - `kmeans`: Integrates the above functions to implement the full K-Means algorithm.

2. **Visualization**:
   - The final clustering results are visualized using `matplotlib`, displaying:
     - Data points color-coded by cluster.
     - Red markers for cluster centers.

---
