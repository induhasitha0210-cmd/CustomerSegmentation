Customer Segmentation using K-Means Clustering
Overview

This project performs customer segmentation using the K-Means clustering algorithm. The goal is to group customers based on their Annual Income and Spending Score to help businesses understand customer behavior and create targeted marketing strategies.

Dataset

The dataset used is Mall_Customers.csv, which contains:

Column	Description
CustomerID	Unique ID for each customer
Gender	Customer gender (Male/Female)
Age	Age of the customer
Annual Income (k$)	Customer income in thousand dollars
Spending Score (1-100)	Score assigned by the mall based on customer behavior
Steps in the Project

Import Libraries: pandas, matplotlib, sklearn

Load Dataset: Read Mall_Customers.csv into a DataFrame

Feature Selection: Use Annual Income and Spending Score

Elbow Method: Determine the optimal number of clusters

K-Means Clustering: Apply K-Means with the chosen number of clusters

Visualization: Scatter plot of clusters with centroids

Cluster Insights

Cluster 1 → High income, high spending

Cluster 2 → High income, low spending

Cluster 3 → Moderate income and spending

Cluster 4 → Low income, high spending

Cluster 5 → Low income, low spending

(You can adjust these labels based on your analysis.)

How to Run


Make sure the CSV is in the same folder as the script.

Install dependencies:

pip install pandas matplotlib scikit-learn


Run the script:

python customer_segmentation.py

Libraries Used

pandas – for data manipulation

matplotlib – for visualization

scikit-learn – for K-Means clustering

Author

Indu Hasitha


Machine Learning Intern
