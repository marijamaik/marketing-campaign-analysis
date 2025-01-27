# Marketing Campaign Analysis with Unsupervised Learning
## Overview
This project focuses on applying Unsupervised Learning techniques to segment customers based on shared characteristics. Using clustering and dimensionality reduction, the goal is to create meaningful customer groups that can be targeted with tailored marketing strategies to improve business efficiency and marketing ROI.

## Objective
The aim is to identify distinct customer segments from a given dataset using clustering algorithms and dimensionality reduction. These segments will allow businesses to tailor marketing efforts more effectively.

## Tools and Techniques
### Programming Language: Python 3.8

### Libraries:
- Data Manipulation: Pandas, NumPy
- Data Visualisation: Matplotlib, Seaborn
- Preprocessing: Scikit-learn (StandardScaler, LabelEncoder)
- Clustering: Scikit-learn (KMeans, DBSCAN, AgglomerativeClustering, GaussianMixture), sklearn_extra (KMedoids)
- Dimensionality Reduction: PCA, t-SNE
- Distance Computation: SciPy (cdist, pdist)
- Metrics & Evaluation: Silhouette score, Cophenetic Correlation
- Visualisation Tools: Yellowbrick (SilhouetteVisualizer)

### Techniques:
- Clustering (K-Means, DBSCAN, Agglomerative Clustering, K-Medoids, Gaussian Mixture)
- Dimensionality Reduction (PCA, t-SNE)
- Data Preprocessing and Feature Scaling
- Data Visualisation (Elbow Curve, Silhouette Scores)

## Data Dictionary

The dataset includes the following features:

### Customer Information
- ID: Unique identifier for each customer
- Year_Birth: Year the customer was born
- Education: Customer's highest level of education
- Marital_Status: Customer's marital status
- Kidhome: Number of young children in the household
- Teenhome: Number of teenagers in the household
- Income: Annual household income
- Recency: Days since the last purchase
- Dt_Customer: Date when the customer joined

### Spending Behavior (Last 2 Years)
- MntFishProducts: Spending on fish products
- MntMeatProducts: Spending on meat products
- MntFruits: Spending on fruits
- MntSweetProducts: Spending on sweets
- MntWines: Spending on wine
- MntGoldProds: Spending on gold products

### Purchase Activities
- NumDealsPurchases: Purchases made with discounts
- NumCatalogPurchases: Purchases made through catalogs
- NumStorePurchases: In-store purchases
- NumWebPurchases: Purchases made on the company website
- NumWebVisitsMonth: Number of website visits in the past month

### Campaign Interactions
- AcceptedCmp1 to AcceptedCmp5: 1 if the customer accepted the offer in the respective campaign, 0 otherwise
- Response: 1 if the customer accepted the offer in the last campaign, 0 otherwise

### Customer Feedback
- Complain: 1 if the customer complained in the past 2 years, 0 otherwise
