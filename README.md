# Unsupervised Learning, Python

## Repository Content
Unsupervised Learning/
│── README.md
│── Avance_Proyecto_Parte_04.ipynb
│── data/
│   └── (datasets utilizados)
│── outputs/
│   ├── gráficos/
│   └── tablas/
│── src/
│   └── funciones_utiles.py

This repository contains the development corresponding to Unsupervised Learning, focused on analysis techniques, data preparation and exploratory modeling within the context of the EBAC program.

## Project Objective
The purpose of this stage is to advance the analysis of the assigned dataset, applying preprocessing, exploration, visualization, and initial modeling techniques, in order to prepare the foundation for the following phases of the project.


## Project Goals
- Clean and prepare retail transaction data.
- Build RFM variables to evaluate customer behavior.
- Standardize the data with StandardScaler.
- Apply K-Means to segment customers.
- Evaluate the clusters and generate actionable insights for the business.

 Technologies and Libraries
Python 3
Pandas – Data manipulation
NumPy – Numerical operations
Seaborn / Matplotlib – Visualization
Scikit-learn
StandardScaler
KMeans

RFM Methodology
The RFM model allows evaluating customers based on:
Recency: How recently they made a purchase.
Frequency: How often they purchase.
Monetary: How much money they spend.

These metrics are transformed and standardized to feed the clustering algorithm.

 Clustering Algorithm
K-Means is used to identify groups of customers with similar behaviors.
The process includes:
Selecting the optimal number of clusters (elbow method).
Training the model.
Assigning cluster labels to each customer.
Interpreting the segments.

Results and Conclusions
The analysis allows identifying different types of customers, for example:
High-value customers
Frequent but low-spending customers
Inactive customers
Occasional buyers

These segments can be used for: Personalized marketing campaigns Loyalty programs Promotion optimization Retention strategies
