# Customer-Segmentation-Analysis

This project involves analyzing customer data to segment them based on their purchasing behavior using clustering algorithms. The goal is to understand different types of customers and tailor marketing strategies accordingly.

Table of Contents
Project Description
Data
Requirements
Project Structure
Analysis
Results
Usage
Contributing
License
Project Description
Customer segmentation is crucial for businesses to target specific groups with personalized marketing, leading to higher customer satisfaction and retention. This project uses K-means clustering to segment customers based on various features such as age, income, spending score, and purchase frequency.

Data
The dataset includes the following columns:

id: Customer ID
age: Age of the customer
gender: Gender of the customer
income: Annual income of the customer
spending_score: Spending score assigned by the store
membership_years: Number of years the customer has been a member
purchase_frequency: Number of purchases made by the customer
preferred_category: The category of products most frequently purchased by the customer
last_purchase_amount: Amount spent on the last purchase
Note: There are no missing values in the dataset.

Requirements
The project requires the following Python libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn

Analysis
Step 1: Load and Explore the Data
The dataset is loaded into a pandas DataFrame and the first few rows are displayed to understand its structure.

Step 2: Preprocess the Data
Relevant numerical features are selected and standardized using StandardScaler to prepare for clustering.

Step 3: Apply K-means Clustering
The Elbow method is used to determine the optimal number of clusters, followed by the application of K-means clustering.

Step 4: Analyze and Interpret the Clusters
The clusters are analyzed by calculating the mean of each numeric feature for every cluster, helping to interpret the characteristics of each customer segment.

Step 5: Visualize the Clusters
Principal Component Analysis (PCA) is used to reduce the dimensions of the data, and the clusters are visualized in a 2D plot.

Results
The analysis results in customer segments based on their purchasing behavior. Each cluster represents a group of customers with similar characteristics, which can be used to tailor marketing strategies.

Usage
To run the analysis:

Clone this repository.
Ensure you have the required dependencies installed.
Run the Jupyter notebook customer_segmentation.ipynb in the analysis folder.

This README file should provide a clear overview of your project, making it easier for others to understand and use your analysis.
