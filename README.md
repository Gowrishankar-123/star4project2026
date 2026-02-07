# star4project2026
# K-Means Clustering From Scratch
## Description

This project implements the K-Means clustering algorithm manually in Python without using the built-in sklearn KMeans function.
The program groups similar data points into clusters and evaluates the clustering performance.
It also finds the optimal number of clusters using the Elbow Method, checks accuracy using Silhouette Score, and visualizes the clusters using PCA.

This project belongs to *Machine Learning (Unsupervised Learning).

## Tools & Libraries Used

 Python
 NumPy
 Matplotlib
 Scikit-learn (only for dataset generation, PCA and evaluation)

## Dataset

Synthetic dataset generated using make_blobs():

 500 data points
 4 features
 3 clusters

## Working

1. Randomly initialize centroids
2. Assign each point to the nearest centroid
3. Update centroids by calculating the mean
4. Repeat until centroids stop changing

## Methods Used

 Elbow Method (to find optimal K)
 SSE / WCSS calculation
 Silhouette Score (cluster quality)
 PCA (4D data → 2D visualization)

## Output

The program produces:
 Elbow graph
 Silhouette score in terminal
 Cluster visualization plot


## How to Run

Install required packages:
pip install numpy matplotlib scikit-learn
Run the program:
python kmeans_from_scratch.py

## Conclusion

The K-Means algorithm was successfully implemented from scratch.
The optimal number of clusters was found to be *3*, and the clustering result was visualized using PCA.




