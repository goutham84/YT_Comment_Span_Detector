# YouTube Comment Classification Using Clustering Algorithms

## Project Overview

This project explores the application of clustering algorithms followed by ouliers detection algorithms to classify YouTube comments. Given the vast amount of unstructured data generated on platforms like YouTube, clustering and outliers detection techniques offer a scalable method to organize and analyze this data. In this project, several unsupervised learning methods, including **K-Means**, **DBSCAN**, and **Hierarchical Clustering**, were implemented to group comments based on their similarities, various Ouliers detection techniques were also implemented which includes **LOF**, **Z-Score** and **One Class SVM**.

The primary goal is to identify spam comments, which can assist in sentiment analysis, community engagement, and spam detection.

## Methods

The project follows a well-defined machine learning pipeline consisting of:

1. **Data Preprocessing:** Cleaning and preparing the text data for clustering.
2. **Text Preprocessing:** Applying techniques like tokenization, stemming, lemmatization, and stopword removal using the NLTK library.
3. **Vectorization:** Using TF-IDF for converting text into numerical features.
4. **Clustering Algorithms:**
   - **K-Means Clustering**
   - **DBSCAN**
   - **Agglomerative Hierarchical Clustering**
5. **Dimensionality Reduction:** Principal Component Analysis (PCA) was applied to improve clustering performance and visualization.
6. **Outliers Detection Algorithms**:
   - **Z-Score**
   - **LOF**
   - **One Class SVM**
7. **Ensemble Model**
8. **Supervised training on the predicted data from Ensemble model**
9. **Predictions on remaining data**


## Results
For the dataset Outliers Detection Algorithms performed well as compared to the Clustering algorithms.
