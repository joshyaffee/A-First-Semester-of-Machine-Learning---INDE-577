## Clustering Algorithms

Clustering is an unsupervised learning technique used to group similar data points together. The goal of clustering is to find patterns and structure within the data without any prior knowledge of the groups or labels. Clustering algorithms are used to partition data points into groups, called clusters, based on similarity or distance between the points.

K-means is a popular clustering algorithm that aims to partition the data into a fixed number of clusters. The algorithm starts by randomly selecting k centroids, which represent the center of the initial clusters. The algorithm then assigns each data point to the closest centroid, and recalculates the centroids as the mean of the assigned data points. This process continues until the centroids converge, and the data points are assigned to their final clusters.

DBScan is another popular clustering algorithm that is often used for data with irregular shapes and varying densities. The algorithm starts by selecting a random point and expanding the cluster by adding nearby points that satisfy a given distance threshold. This process continues until no more points can be added to the cluster, and the algorithm then starts a new cluster with another unvisited point.

Different datasets are better fit by different clustering algorithms depending on the characteristics of the data. For example, K-means is a good choice when the data is dense and has a clear structure, while DBScan is better suited for data with varying densities and irregular shapes. Other clustering algorithms, such as hierarchical clustering or spectral clustering, may be better suited for other types of data. It's important to explore different clustering algorithms and evaluate their performance on the specific dataset to choose the most appropriate algorithm for the task.

Within the notebook you may find an explanation of how the models work as well as an application to the cbb dataset. Furthermore, there is the implementantion and application of a bonus clustering algorithm inspired by graph theory!
