# K-Means

I used to define a cluster system respecto to arbitrary initialized particles. Number of particles, centroids are caahangeble by user, also grid size too.

Algorithm:

1. #particles created
2. #centroids created overlapping on particles
3. Respect to numbers of centroids, closest particles defined (Euclidean distance is the measure of distance) and their average point is new centroid position.
4. Cost function is found by sum of each distance by centroid and corresponding cluster particle
5. Repeat from number 2 to 4 until to #particles.
6. The lowest Cost function is given by best suited centroid position.

Elbow Method: (Choosing #Cluster)

More suitable number of clusters of a given system, should be found by when the plot of Cost Function vs. Number of Cluster distortion slows down.

However, more offenly curve does not have clear elbow. Thus, I thought that choosing number of cluster depends on raw data and the requirament of system.     
