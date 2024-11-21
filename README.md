# Data Analysis Project
## Project Overview
In this project, we perform a customer segmentation analysis using the KMeans clustering algorithm on a retail dataset from a mall. The goal is to segment customers based on their age, annual income, and spending score, allowing businesses to better understand and target different customer groups.
## Dataset
The dataset used in this project is the "Mall Customer Segmentation Data," which contains information about 200 customers of a shopping mall. The key features include:

- **Age**: The age of the customer.
- **Annual Income** (k$): The annual income of the customer in thousands of dollars.
- **Spending Score** (1-100): A score assigned by the mall based on customer behavior and spending patterns.
## Objectives

- Preprocess the data by selecting relevant features and standardizing them.
- Apply KMeans clustering to segment customers into groups based on their behavior.
- Visualize the clusters using scatter plots to better understand customer segments.
## Key Steps:

### 1. Data Preprocessing:
- **Loaded the dataset**: The dataset contains customer data including **Age**, **Annual Income (k$)**, and **Spending Score (1-100)**.
- **Feature selection**: Relevant features were selected for clustering, specifically:
  - **Age**
  - **Annual Income (k$)**
  - **Spending Score (1-100)**
- **Standardized the data**: To ensure fair clustering, I used the `StandardScaler` from `scikit-learn` to standardize the data. This step is essential because KMeans is sensitive to the scale of features.

### 2. Clustering with KMeans:
- **Applied KMeans clustering**: I used the KMeans algorithm to segment customers into **4 clusters** based on the selected features. The number of clusters was chosen after performing an analysis.
### 3. Visualization:
- **Scatter plot creation**: A scatter plot was created to visualize the customer segments based on their **Annual Income** and **Spending Score**.
- **Cluster representation**: Each cluster is represented by a different color, making it easy to understand the distribution and characteristics of each customer group.

  ## Tools & Libraries Used

This project utilizes several powerful Python libraries for data manipulation, clustering, and visualization:

- **Pandas**: For data manipulation and cleaning.
  
- **Scikit-learn**: For implementing KMeans clustering and data scaling.
  
- **Seaborn & Matplotlib**: For creating visualizations (scatter plots).

