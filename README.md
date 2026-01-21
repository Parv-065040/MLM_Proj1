Supply Chain Transportation Clustering Analysis
Project Overview

This project presents an end-to-end data analytics and machine learning workflow applied to supply chain transportation data. The objective is to uncover hidden patterns in logistics operations by combining exploratory data analysis, dimensionality reduction, and unsupervised learning techniques.

The analysis supports data-driven decision-making by identifying cost, distance, and efficiency-based clusters within transportation operations.

Problem Statement

Supply chain and logistics operations involve multiple variables such as transportation cost, distance traveled, vehicle capacity, delivery frequency, and environmental conditions. Analyzing such high-dimensional data using traditional methods can be inefficient and misleading.

This project addresses the problem by applying clustering techniques to group similar transportation patterns, enabling better operational insights and optimization opportunities.

Objectives

Perform data cleaning and preprocessing on logistics data

Conduct exploratory data analysis to understand key trends and distributions

Reduce dimensionality using Principal Component Analysis (PCA)

Apply and compare multiple clustering algorithms

Evaluate clustering quality using standard metrics

Generate actionable business insights for supply chain optimization

Dataset Description

The dataset contains transportation and logistics-related attributes, including product characteristics, transportation methods, vehicle information, cost, distance, and delivery conditions.

Key variables include:

Product category and quantity

Transportation method

Vehicle type and capacity

Transportation cost

Distance traveled

Temperature and humidity maintenance

Delivery frequency and transit time

Damage and tracking indicators

Tools and Technologies

Python

Google Colab

Pandas and NumPy

Matplotlib and Plotly for visualization

Scikit-learn for preprocessing, dimensionality reduction, and clustering

Methodology
Data Preprocessing

Missing values handled using appropriate imputation techniques

Low-variance features removed to improve model efficiency

Categorical variables encoded

Numerical variables scaled using StandardScaler

Exploratory Data Analysis

Category-wise distribution analysis

Transportation cost distribution analysis

Distance versus cost relationship analysis

Correlation analysis using heatmaps

Dimensionality Reduction

Principal Component Analysis applied to reduce feature space

Optimal number of components selected based on explained variance

Reduced dimensions used as input for clustering algorithms

Clustering Techniques

The following unsupervised learning algorithms were implemented and compared:

K-Means Clustering

DBSCAN

Agglomerative Clustering

Spectral Clustering

Clustering was performed on PCA-transformed data to improve separability and performance.

Model Evaluation

Clustering performance was evaluated using:

Silhouette Score

Davies–Bouldin Index

A comparative assessment was conducted to determine the most effective clustering approach for the dataset.

Key Insights

Distinct transportation clusters were identified based on cost, distance, and vehicle usage

Certain clusters indicated inefficient, high-cost transportation patterns

PCA significantly improved clustering quality and interpretability

K-Means and Spectral Clustering produced more stable and meaningful clusters compared to density-based approaches

Business Implications

Helps identify cost-intensive logistics segments

Supports optimization of transportation and vehicle allocation

Enables data-driven operational and strategic planning

Applicable to real-world supply chain and logistics decision-making

Future Scope

Incorporation of time-series analysis for demand and delivery trends

Predictive modeling for transportation cost forecasting

Integration with visualization tools such as Power BI or Tableau

Automation of the clustering and evaluation pipeline

Author

Parv
