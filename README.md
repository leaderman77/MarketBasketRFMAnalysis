# MarketBasketRFMAnalysis
GroceryRFM-Segmentation: "Advanced Customer Segmentation for Grocery Shopping Data"

# Project Overview
This project employs advanced clustering techniques to analyze a dataset of 38,765 grocery store transactions for customer segmentation. The main objective is to use RFM (Recency, Frequency, Monetary) analysis to identify distinct customer segments and derive actionable insights for targeted marketing strategies.

# Data Set Information
Attributes:

- Member Number: Unique identifier for each customer.
- Item Description: Name of the purchased product.
- Date: Timestamp of the transaction.
# Project Structure
1. Data Understanding
- Distribution Analysis: Exploring the distribution of key variables.
- Statistical Exploration: Statistical properties of the dataset.
- Data Transformation and Cleaning: Addressing missing values and transforming variables for better analysis.
- UML Class Diagram: Identifying main classes and associations with cardinality constraints for a better structural understanding.
- Data Visualization: Visual aids to illustrate data properties and preliminary insights.
2. RFM Segmentation
- SQL/Python Implementation: Developing RFM metrics using SQL and Python to classify customers based on transaction recency, frequency, and monetary value.
3. Clustering Analysis
- K-Means, DBSCAN and Agglomerative Clustering: Implementation and testing of clustering models to segment customers.
- Cluster Profiling: Discussion of each cluster's characteristics and the suitability of clustering methods based on silhouette scores and practical segmentation needs.
4. Review of Results
- Business Implications: Analysis of the business value of identified customer segments in terms of marketing strategies, customer loyalty, and lifetime value enhancement.
5. Data Mart Design
- Dimensions and Metrics: Suggestion of relevant dimensions and metrics for a data mart designed to support the marketing department's analysis needs.
# Methodology
Clustering Techniques Used
- K-Means
- DBSCAN: Detailed testing to identify the best values for ε and minPts.
- Agglomerative Clustering: Provided the most meaningful customer segmentation with a silhouette score of 0.54, indicating moderate cluster separation.
# Conclusions
- Evaluation of Clustering Methods: Comparison of clustering methods with a focus on their effectiveness in segmenting the dataset. Agglomerative Clustering was found to be most suitable due to its ability to form well-differentiated customer clusters.
- Recommendations for Marketing Strategies: Based on the clustering results and the defined customer segments, recommendations for targeted marketing actions are proposed.
# Repository Contents
- data/: Scripts for data simulation and instructions for accessing the original dataset.
- code/: All code files, including Jupyter notebooks and SQL scripts.
- reports/: Detailed report aimed at marketing strategists, including the UML class diagram and cluster profiles.
- requirements.txt: Required libraries and dependencies to run the project.
