# Customer Segmentation using K-Means Clustering

## Project Overview

This project performs customer segmentation using the K-Means clustering algorithm.

The main objective is to divide customers into meaningful groups based on their:

- Age
- Annual Income
- Spending Score

The resulting customer segments can help businesses understand customer behavior and develop targeted marketing strategies.

## Dataset

The project uses the Mall Customers dataset.

Dataset features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Machine Learning Algorithm

K-Means Clustering is an unsupervised machine learning algorithm used to divide data into groups called clusters.

## Project Workflow

1. Load the dataset
2. Check missing values and duplicates
3. Select relevant features
4. Standardize the features
5. Use the Elbow Method to determine the number of clusters
6. Apply K-Means Clustering
7. Visualize the customer clusters
8. Analyze each customer segment
9. Calculate the Silhouette Score
10. Save the clustering results

## Features Used

The following features are used for clustering:

- Age
- Annual Income (k$)
- Spending Score (1-100)

The features are standardized using `StandardScaler`.

## Choosing the Number of Clusters

The Elbow Method is used to evaluate different values of K.

For the standard Mall Customers dataset, K = 5 is used for the final model.

## Customer Segments

The clusters are interpreted according to their income and spending behavior.

Typical segments include:

### High Value Customers
Customers with relatively high income and high spending.

**Marketing strategy:**
- VIP membership
- Premium products
- Exclusive offers

### High Income Low Spending
Customers with high income but relatively low spending.

**Marketing strategy:**
- Personalized recommendations
- Premium product promotions
- Special campaigns

### Low Income High Spending
Customers with lower income but high spending.

**Marketing strategy:**
- Loyalty rewards
- Discounts
- Bundle offers

### Low Income Low Spending
Customers with lower income and lower spending.

**Marketing strategy:**
- Budget products
- Discounts
- Promotional campaigns

### Middle/Average Customers
Customers with moderate income and spending behavior.

**Marketing strategy:**
- Regular promotions
- Product recommendations
- Cross-selling

## Evaluation

The project uses the Silhouette Score to evaluate the quality of the clustering.

A higher Silhouette Score generally indicates better-defined clusters.

## Results

The project generates:

- Elbow Method visualization
- Customer segmentation visualization
- Clustered customer dataset
- Cluster profile report

## Output Files

```text
results/
├── elbow_method.png
├── customer_segments.png
├── clustered_customers.csv
└── cluster_profile.csv
