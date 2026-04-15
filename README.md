# MSCS 634 – Project Deliverable 3
## Classification, Clustering, and Pattern Mining

## Overview
This project applies classification, clustering, and association rule mining techniques to analyze customer behavior and support data-driven decision-making.

## Dataset
The dataset contains customer demographics, purchasing behavior, and campaign response data.

Target variable:
Response – indicates whether a customer accepted a marketing campaign offer.

## Data Preparation
- Handled missing values in Income
- Removed duplicates
- Created features: Age, Total_Spending, Children
- Applied StandardScaler

## Classification
Models used:
- Decision Tree
- k-NN
- Tuned k-NN (GridSearchCV)

Evaluation:
- Accuracy
- F1 Score
- Confusion Matrix
- ROC Curve

Key result:
Tuned k-NN performed best with improved F1 score.

## Clustering
Method:
- K-Means (k=3)

Findings:
- Cluster 0: Low-value customers
- Cluster 1: High-value customers
- Cluster 2: Moderate customers

## Association Rule Mining
Method:
- Apriori

Findings:
- Product combinations are common
- Lift values (~1.1) indicate weak but consistent relationships

## Applications
- Customer segmentation
- Targeted marketing
- Product recommendations
- Campaign prediction

## Challenges
- Class imbalance → solved using F1 score
- Parameter tuning → solved using GridSearchCV
- Weak association rules → interpreted carefully

## Conclusion
This project demonstrates how multiple data mining techniques can be used together to generate insights and improve business decision-making.
