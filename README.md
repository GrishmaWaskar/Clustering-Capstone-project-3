# Crime Data Clustering Project.

# Overview of Project

- This project aims to analyze crime data to identify patterns and segment the data into meaningful groups using clustering techniques.
- Two clustering algorithms, Hierarchical Clustering and K-means Clustering, are applied to the dataset to achieve this objective.
- The project involves loading the dataset, performing clustering analysis, visualizing the results, and drawing insights from the data.

# Dataset

The dataset contains information about crime rates in different places of the United States. The features included in the dataset are as follows:

- Murder: Murder rates
- Assault: Assault rates
- UrbanPop: Urban population
- Rape: Rape rates

The dataset is provided in a CSV file named crime_data.csv.

# Libraries Used

- pandas: For data manipulation and analysis
- numpy: For numerical computations
- matplotlib and seaborn: For data visualization
- sklearn: For implementing clustering algorithms

# Clustering Techniques

## Hierarchical Clustering
- Hierarchical clustering is performed using the AgglomerativeClustering algorithm with the Ward linkage method.
- This method recursively merges the pair of clusters that minimally increases a given linkage distance.
- The number of clusters is determined based on the dendrogram generated from the linkage matrix.
  
## K-means Clustering
- K-means clustering is performed using the KMeans algorithm.
- This algorithm partitions the data into K clusters by iteratively assigning data points to the nearest cluster centroid and updating the centroids.
- The optimal number of clusters is determined using the elbow method.

# Results
- The results of the clustering analysis are visualized using pairplot, which displays pairwise relationships between different features in the dataset.
- The clusters formed by both hierarchical and K-means clustering algorithms are displayed in the pairplot, allowing for easy interpretation of the results.

# Conclusion
- This project demonstrates how clustering techniques can be applied to crime data to identify distinct patterns and group similar locations together.
- By analyzing the clusters formed, law enforcement agencies and policymakers can gain insights into crime trends and develop targeted strategies for crime prevention and intervention.
