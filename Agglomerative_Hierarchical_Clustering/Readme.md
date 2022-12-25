# Agglomerative_Hierarchical_Clustering


### What is Clustering??
Clustering is a technique that groups similar objects such that the objects in the same group are more similar to each other than the objects in the other groups. The group of similar objects is called a Cluster.
![](https://miro.medium.com/max/561/0*ff7kw5DRQbs_uixR.jpg)

### Hierarchical Clustering
![](https://miro.medium.com/max/257/0*iozEcRXXWXbDMrdG.gif)

### Types of Agglomerative Hierarchical Clustering
- `Complete-linkage:` the distance between two clusters is defined as the longest distance between two points in each cluster.
- `Single-linkage:` the distance between two clusters is defined as the shortest distance between two points in each cluster. This linkage may be used to detect high values in your dataset which may be outliers as they will be merged at the end.
- `Average-linkage:` the distance between two clusters is defined as the average distance between each point in one cluster to every point in the other cluster.
- `Centroid-linkage:` finds the centroid of cluster 1 and centroid of cluster 2, and then calculates the distance between the two before merging.

### What is a Dendrogram?
A Dendrogram is a type of tree diagram showing hierarchical relationships between different sets of data.
![](https://miro.medium.com/max/480/0*BfO2YN_BSxThfUoo.gif)

### Dendogram of mall_customers dataset
![](https://miro.medium.com/max/666/1*hm9-QiOveg7_BjbEkOXamg.png)

### Cluster of customers formed using hierarchical clustering
![](https://miro.medium.com/max/666/1*lNULBkn7hyYZ5yPkIp8iKg.png)
