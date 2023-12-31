# Unsupervised Learning in Python

## Course Description

> Say you have a collection of customers with a variety of characteristics such as age, location, and financial history, and you wish to discover patterns and sort them into clusters. Or perhaps you have a set of texts, such as Wikipedia pages, and you wish to segment them into categories based on their content. This is the world of unsupervised learning, called as such because you are not guiding, or supervising, the pattern discovery by some prediction task, but instead uncovering hidden structure from unlabeled data. Unsupervised learning encompasses a variety of techniques in machine learning, from clustering to dimension reduction to matrix factorization. In this course, you'll learn the fundamentals of unsupervised learning and implement the essential algorithms using scikit-learn and SciPy. You will learn how to cluster, transform, visualize, and extract insights from unlabeled datasets, and end the course by building a recommender system to recommend popular musical artists.

## Course Chapters

### [Chapter 1: Clustering for Dataset Exploration](https://github.com/PavlosIsaris/Unsupervised-Learning-in-Python/tree/main/1_Clustering_for_Dataset_Exploration)

> Learn how to discover the underlying groups (or "clusters") in a dataset. By the end of this chapter, you'll be clustering companies using their stock market prices, and distinguishing different species by clustering their measurements.

#### Chapter 1 Details

* Unsupervised Learning (introduction)
* Clustering 2D points
* Inspecting / Evaluating your clustering
* Evaluating the grain clustering
* Transforming features for better clusterings
* Scaling data for clustering
* Which points move together?

### [Chapter 2: Visualization with Hierarchical Clustering and t-SNE](https://github.com/PavlosIsaris/Unsupervised-Learning-in-Python/tree/main/2_Visualization_with_Hierarchical_Clustering_and_t-SNE)

> In this chapter, you'll learn about two unsupervised learning techniques for data visualization, hierarchical clustering and t-SNE. Hierarchical clustering merges the data samples into ever-coarser clusters, yielding a tree visualization of the resulting cluster hierarchy. t-SNE maps the data samples into 2d space so that the proximity of the samples to one another can be visualized.

#### Chapter 2 Details

* Visualizing hierarchies
* Cluster labels in hierarchical clustering
* Different linkage, different hierarchical clustering
* t-SNE for 2-dimensional maps
* t-SNE visualization of datasets

### [Chapter 3: Decorrelating Your Data and Dimension Reduction](https://github.com/PavlosIsaris/Unsupervised-Learning-in-Python/tree/main/3_Decorrelating_Your_Data_and_Dimension_Reduction)

> Dimension reduction summarizes a dataset using its common occurring patterns. In this chapter, you'll learn about the most fundamental of dimension reduction techniques, "Principal Component Analysis" ("PCA"). PCA is often used before supervised learning to improve model performance and generalization. It can also be useful for unsupervised learning. For example, you'll employ a variant of PCA will allow you to cluster Wikipedia articles by their content!

#### Chapter 3 Details

* Visualizing the PCA transformation
* Principal Components
* Intrinsic Dimension
* PCA Features
* Dimension reduction with PCA
* A tf-idf word-frequency array

### [Chapter 4: Discovering Interpretable Features](https://github.com/PavlosIsaris/Unsupervised-Learning-in-Python/tree/main/4_Discovering_Interpretable_Features)

> In this chapter, you'll learn about a dimension reduction technique called "Non-negative matrix factorization" ("NMF") that expresses samples as combinations of interpretable parts. For example, it expresses documents as combinations of topics, and images in terms of commonly occurring visual patterns. You'll also learn to use NMF to build recommender systems that can find you similar articles to read, or musical artists that match your listening history!

#### Chapter 4 Details

* Non-negative matrix factorization ("NMF")
* NMF applied to Wikipedia articles
* Building a recommender system using NMF
* Recommend musical artists