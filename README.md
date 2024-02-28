
# Unsupervised learning

Unsupervised learning in artificial intelligence is a sort of machine learning that learns from data without human intervention. In contrast to supervised learning, unsupervised machine learning models are given unlabeled data and allowed to identify patterns and insights without explicit direction or instruction. 

Whether you know it or not, artificial intelligence and machine learning are influencing every area of daily life, assisting in the conversion of data into insights that can enhance efficiencies, lower costs, and inform decision-making. Today, organizations use machine learning algorithms to enable tailored recommendations, real-time translations, and even the autonomous generation of text, images, and other sorts of content.


# Clustering
  
  Clustering is a sort of unsupervised learning in which the references come from unlabeled datasets. In general, it is used to capture the relevant structure, underlying processes, and grouping of a dataset. Clustering is the process of dividing a population into many groups so that data points in the same groups are more similar to one another than data points in other groups. Clustering allows data scientists to uncover intrinsic groupings among unlabeled data. Though there are no specific criteria for a good clustering, it is entirely up to the user and how they want to use it for their specific requirements. It can be used to locate uncommon data points/outliers in the data, as well as to identify unknown features in order to organize the dataset appropriately.


# Types of clustering 

There are various clustering methods that can handle a wide range of unique data.

## Density-based

- Density-based clustering divides data into areas with high data point concentrations and areas with low data point concentrations. Essentially, the algorithm identifies and names clusters based on the density of data points.

- The beautiful thing about this is that the clusters can take any shape. You are not limited to the predicted conditions.

- Outliers are ignored by this sort of clustering technique since it does not attempt to assign them to clusters.

## Distribution-based
- A distribution-based clustering approach considers all data points to be part of a cluster based on their probability of belonging to that cluster.

- When using a distribution-based clustering technique, each data point is regarded as a component of a cluster according to the likelihood that it is a part of a particular cluster.

- This is how it operates: a cluster has a center, and a data point's likelihood of belonging to that cluster diminishes with increasing distance from the center.

- A different kind of algorithm should be taken into consideration if you are unsure of the possible distribution of your data.

## Centroid-oriented

- The most common type of clustering is presumably centroid-based clustering. Although it is quick and effective, it is a little sensitive to the first parameters you give it.

- These kinds of algorithms divide data points according to several data centroids. A cluster is formed from each data point according to its squared distance from the centroid. The most popular kind of clustering is this one.

## Hierarchy-based

- Usually, hierarchical data—such as that found in taxonomies or enterprise databases—is used for hierarchical-based clustering. In order to organize everything top-down, it creates a tree of clusters.Although it has more limitations than the other clustering techniques, this works well with particular sorts of data sets.




# K-Means-Clustering

- K-means clustering is the most used clustering algorithm. It is the most basic unsupervised learning algorithm, based on centroid calculations.

- This program aims to reduce the variability of data points inside a cluster. It is also the most common way for individuals to learn about unsupervised machine learning.

- K-means works better with smaller data sets because it iterates over all of the data points. That is, if the data collection has a huge number of data points, classifying them will take longer.

- This is how k-means clusters data points, and it does not scale well.

