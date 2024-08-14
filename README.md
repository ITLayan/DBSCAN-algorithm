I have tried one of the ML algorithms, which is DBSCAN, It's used for clustering  by picking a random point and then determining the point type, if it is core border or outlier.
Once a core point has been found, add all directly reachable points to the same cluster as core.
 Repeat until all points have been assigned to a cluster or as an outlier.
 
<img width="420" alt="fa1" src="https://github.com/user-attachments/assets/964bd394-88d2-43ac-b722-4a1915b2ddb0">

Like here I choose the epsilon 0.82 and number of points = 3 so we have 7 clusters

<img width="421" alt="fa2" src="https://github.com/user-attachments/assets/ab3d14cc-01e4-4675-875b-976c1b227f2e">

Here, I changed the epsilon to the largest value and the number of points to 6. As we see, the number of clusters was altered to 3 clusters.
https://www.naftaliharris.com/blog/visualizing-dbscan-clustering/ 
A fun experience, I recommend trying it.

