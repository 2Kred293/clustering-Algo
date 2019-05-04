# clustering-Algo
types of clustering algorithms


Objective: Aim is to use clustering algorithms to bifurcate students of a school on the basis of height and weight for the      school's events
 Algorithms used to find comparable centroids: Kmeans and Mean-shift
 
 
 -By finding the centroids amongst the dataset provided, we have points along which the students are categorised into groups for their annual day event.
 
 
 INTRO to K-means
 
 K-means clustering is a type of unsupervised learning, which is used when you have unlabeled data (i.e., data without defined categories or groups). The goal of this algorithm is to find groups in the data, with the number of groups represented by the variable K. The algorithm works iteratively to assign each data point to one of K groups based on the features that are provided. Data points are clustered based on feature similarity. The results of the K-means clustering algorithm are:

1)The centroids of the K clusters, which can be used to label new data
2)Labels for the training data (each data point is assigned to a single cluster)

INTRO to Mean-Shift algorithm

Meanshift is a clustering algorithm that assigns the datapoints to the clusters iteratively by shifting points towards the mode. The mode can be understood as the highest density of datapoints (in the region, in the context of the Meanshift). As such, it is also known as the mode-seeking algorithm. Meanshift algorithm has applications in the field of image processing and computer vision.

Given a set of datapoints, the algorithm iteratively assign each datapoint towards the closest cluster centroid. The direction to the closest cluster centroid is determined by where most of the points nearby are at. So each iteration each data point will move closer to where the most points are at, which is or will lead to the cluster center. When the algorithm stops, each point is assigned to a cluster.

About the Data set

The data set is a group of students pertaining the attributes of height and weight. The centroids obtained are used as limits or middle points in a group of points to cluster points around. 

CONCLUSION OF K MEANS

The objective of K-Means clustering is to minimize total intra-cluster variance, or, the
squared error function: Algorithm. Clusters the data into k groups where k is predefined.
Select k points at random as cluster centres. Assign objects to their closest cluster centre
according to the Euclidean distance function. The graph above shows less variation
within clusters which means the data points are within the same cluster making them
more homogenous(similar). In this way, students of the same height and weight can
be put into same group based on the calculations done by the algorithm. (Graph in report)



CONCLUSIONS OF MEAN SHIFT


Based on the calculations done by
the algorithm, the centroid is obtained and all the points close to the centroid form a
homogenous cluster , thereby forming groups of students with similar heights and weights in
order to maintain fair participation.



 
