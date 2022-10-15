# [ML22-2] PHW-2
#description
##data
California Housing Prices
Median house prices for California districts derived from the 1990 census

#funciton description

##objective setting
clustering the california housing prices, so we can know what is the most related feature with the housing prices

# function detail
##mergeDf()
merge the scaled data frame and encoded data frame

##kmeans()
make the kmeans model and return kmeans_labels

##visualize_cluster_plot()
visulaize the cluster model

##gmm()
make the GaussianMixture() model and return gmm_labels

##dbScan()
make the DBSCAN() model and return dbscan.labels

##kmeansElbow_plot()
plot the elbow for kmeans that indicate the best K for the model.

##purity_score()
show the purity score for the clustering model

#process
check the result for different combination of scaling(standard, minmax, robust) and encoding(onehot, label) of data set
