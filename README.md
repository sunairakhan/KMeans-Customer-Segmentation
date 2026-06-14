# Customer Segmentation Using K-Means Clustering

## Assignment Title
K-Means Clustering Implementation

## Project Overview
This project applies K-Means Clustering to segment mall customers based on their Annual Income and Spending Score. The model is trained using the standard Mall Customers dataset and tested using 10 custom customer records.

## Dataset
The project uses two datasets:

1. Standard Dataset: Mall_Customers.csv  
2. Custom Dataset: custom_customers.csv

The custom dataset contains 10 customer records with Age, Annual Income, and Spending Score.

## Features Used for Clustering
The following features were used to train the K-Means model:

- Annual Income (k$)
- Spending Score (1-100)

## Algorithm Used
K-Means Clustering was used in this project. It is an unsupervised machine learning algorithm that groups similar data points into clusters.

## Preprocessing
StandardScaler was used to scale the selected features before applying K-Means. Scaling is important because K-Means uses distance to create clusters.

## Optimal K Selection
The Elbow Method was used to find the optimal number of clusters. Based on the Elbow Curve, K = 5 was selected.

## Model Training
The K-Means model was trained using the scaled standard dataset. After training, the model was saved as a pickle file.

## Custom Data Prediction
The custom customer data was processed using the same fitted scaler. Then the trained K-Means model predicted the cluster ID for each custom customer.

## Output
The notebook displays the following outputs:

1. Elbow Curve Plot
2. Cluster Scatter Plot with Centroids
3. Custom Customer Prediction Table
4. Cluster Centers Table
5. Cluster Interpretation

## Cluster Interpretation
The K-Means model divided the customers into 5 different groups based on Annual Income and Spending Score. Some clusters represent customers with low income and high spending, while others represent customers with high income and low spending. This clustering result can help a business understand customer behavior and make better marketing decisions.
How to Run

Open the Google Colab notebook and click Run All. The notebook will automatically clone the GitHub repository, load the datasets, preprocess the data, train the K-Means model, save the model, predict clusters for custom data, and show all required outputs.

Submitted By

Name: Umma Habiba
Student ID :210117
