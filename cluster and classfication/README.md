# Cluster and classification

## Cluster
Clustering is a Machine Learning technique that involves the grouping of data points. Given a set of data points, data points that are in the same group should have similar properties and/or features, while data points in different groups should have highly dissimilar properties and/or features. Clustering is a method of unsupervised learning and is a common technique for statistical data analysis used in many fields.

Data Scientist use cluster analysis to gain some valuable insights from our data by seeing what groups the data points fall into. There are five most popular algorithms listed as followed with sample project below:

* **K-means**

  Select a number of classes and randomly initialize their respective center points. Compute the distance between each point and each group center to classify the group with closest center to it. Based on these classified points, recompute the group center by taking the mean of all the vectors in the group. 
  
  Example: [Classify tips dataset with Kmeans](https://github.com/LunaYogada/452_machine_learning/blob/master/cluster%20and%20classfication/Classify%20tips%20dataset%20with%20Kmeans.ipynb)

* **Mean-Shift Clustering**

  Mean shift clustering is a sliding-window-based algorithm that attempts to find dense areas of data points. It is a centroid-based algorithm meaning that the goal is to locate the center points of each group/class, which works by updating candidates for center points to be the mean of the points within the sliding-window. These candidate windows are then filtered in a post-processing stage to eliminate near-duplicates, forming the final set of center points and their corresponding groups. 
  
* **Density-Based Spatial Clustering of Applications with Noise (DBSCAN)**

  
* **Gaussian Mixture Models (GMM)**
* **Agglomerative Hierarchical Clustering**

  Hierarchical clustering algorithms actually fall into 2 categories: top-down or bottom-up. Bottom-up algorithms treat each data point as a single cluster at the outset and then successively merge (or agglomerate) pairs of clusters until all clusters have been merged into a single cluster that contains all data points. Bottom-up hierarchical clustering is therefore called hierarchical agglomerative clustering or HAC. This hierarchy of clusters is represented as a tree (or dendrogram). The root of the tree is the unique cluster that gathers all the samples, the leaves being the clusters with only one sample.

## Classfication
In machine learning , classification is the set of categories (sub-populations) a new observation belongs, on the basis of a training set of data containing observations (or instances) whose category membership is known.

Common algorithm:

* **Logistic Regression**
* **support vector machines (svm)**

  [abalone classification](https://github.com/LunaYogada/452_machine_learning/blob/master/cluster%20and%20classfication/abalone%20classification.ipynb)
  
  [Select best SVM parameter by GridSearchCV](https://github.com/LunaYogada/452_machine_learning/blob/master/cluster%20and%20classfication/plot_iris_dataset.ipynb)
* **Decision Trees**
* **Random Forest**
* **Naive Bayes**
