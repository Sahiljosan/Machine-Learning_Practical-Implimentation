# DBScan : Density-based spatial clustering of applications with noise
-------------------------
![](https://i.imgur.com/VKxRV83.jpg)
![](https://miro.medium.com/max/1339/0*xu3GYMsWu9QiKNOo.png)

Code to find WCSS and plot The Elbow Method
```
from sklearn.cluster import KMeans
WCSS = []
for i in range(1,11):
    km = KMeans(n_clusters=i, init = "k-means++", max_iter = 300, n_init= 10)
    km.fit(data)
    WCSS.append(km.inertia_)
plt.plot(range(1,11),WCSS)
plt.scatter(5,WCSS[5], marker = "X", s = 200, c = "red",)
plt.title("The Elbow Method")
plt.xlabel("Number of Clusters")
plt.ylabel("WCSS")
plt.show()
```

DBscan algorithm syntax:
```
from sklearn.cluster import DBSCAN
# Here we have to pass two parameters elsilon and minimum_pts
dbscan = DBSCAN(eps=5,min_samples=5)
labels = dbscan.fit_predict(data)
# Labels are the number of clusters
labels
```

Visualize Clusters, we get from DBscan
```
plt.scatter(data[labels==-1,0],data[labels == -1,1], s = 20, c = "black")
plt.scatter(data[labels==0,0],data[labels == 0,1], s = 20, c = "blue")
plt.scatter(data[labels==1,0],data[labels == 1,1], s = 20, c = "red")
plt.scatter(data[labels==2,0],data[labels == 2,1], s = 20, c = "green")
plt.scatter(data[labels==3,0],data[labels == 3,1], s = 20, c = "mediumvioletred")
plt.scatter(data[labels==4,0],data[labels == 4,1], s = 20, c = "brown")

plt.xlabel("Annual Income")
plt.ylabel("Spending Score")
plt.show()
```
