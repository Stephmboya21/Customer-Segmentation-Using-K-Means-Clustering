# Customer Segmentation Using K-Means Clustering

This project aims to segment customers based on their demographic and purchasing behaviors using the K-Means clustering algorithm. By identifying distinct customer groups, businesses can tailor marketing strategies, improve customer experiences, and optimize product offerings.

## Dataset Information
The dataset consists of the following columns:

- CustomerID: Unique identifier for each customer.
- Gender: Gender of the customer (Male/Female).
- Age: Age of the customer.
- Annual Income (k$): Annual income of the customer in thousand dollars.
- Spending Score (1-100): Score assigned based on customer behavior and purchasing data, ranging from 1 to 100.

## Analysis Process
### 1. Exploratory Data Analysis (EDA)
Before performing clustering, an extensive exploratory analysis was conducted to understand the distribution and relationships between the variables:

- Univariate Analysis: 
   - Distribution of individual features like Age, Annual Income, and Spending Score.
   - Count of customers by Gender.
  
- Bivariate Analysis: 
   - Relationship between two variables. Examples:
     - Scatter plots of Annual Income vs Spending Score to examine potential clusters.
     - Box plots of Age vs Gender to compare spending behavior by gender.
  
- Multivariate Analysis: 
   - Combined analysis of more than two variables to understand interactions and insights.
     - Heatmaps and pair plots to identify correlations between variables like Age, Income, and Spending Score.

### 2. K-Means Clustering
K-Means clustering was applied to group customers based on the following features:
- Age
- Annual Income
- Spending Score

The number of clusters was determined using the **elbow method**, evaluating the sum of squared distances for various cluster sizes.

### 3. Findings and Recommendations

![customerseg](https://github.com/user-attachments/assets/06fdae0b-fda4-491f-9843-3b820cad3d20)

- Target group would be cluster 1 which has a high spending score and high income
- 54% of cluster 1 shoppers are women. We should look for ways to attract these customers using a marketing campaign targeting popular items in this cluster.
- Cluster 2 presents an interesting opportunity to market to the customers for sales event on popular items.

These segments provide valuable insights for targeted marketing strategies and personalized customer engagement.

## Tools and Technologies Used
- **Python**: For data analysis and modeling.
- **Pandas**: Data manipulation and cleaning.
- **Matplotlib & Seaborn**: Data visualization.
- **Scikit-learn**: K-Means clustering implementation.

