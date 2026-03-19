## Customer Segmentation Analysis

### Introduction
This project aims to perform customer segmentation using the K-Means clustering algorithm. The goal is to group customers into distinct segments based on their annual income and spending score, enabling businesses to tailor marketing strategies more effectively.

### Dataset
The analysis uses the `Mall_Customers.csv` dataset, sourced from KaggleHub. This dataset contains customer information including `CustomerID`, `Gender`, `Age`, `Annual Income (k$)`, and `Spending Score (1-100)`.

### Methodology
1.  **Data Loading**: The dataset was loaded into a pandas DataFrame.
2.  **Exploratory Data Analysis (EDA)**: Initial inspection of the data to understand its structure and content.
3.  **Optimal Cluster Determination (Elbow Method)**: The Elbow Method was applied to determine the optimal number of clusters for K-Means. By plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters, an 'elbow' was observed, indicating 5 as the optimal number of clusters.
4.  **K-Means Clustering**: The K-Means algorithm was applied with 5 clusters to segment the customers based on their 'Annual Income (k$)' and 'Spending Score (1-100)'.
5.  **Visualization**: A scatter plot was generated to visualize the distinct customer segments.
6.  **Cluster Analysis**: The mean 'Annual Income (k$)' and 'Spending Score (1-100)' for each cluster were calculated to understand the characteristics of each segment.

### Key Findings: Customer Segments
Based on the K-Means clustering, 5 distinct customer segments were identified:

*   **Cluster 1 (Average Shoppers)**: Customers with a balanced annual income and spending score. These are typical, everyday customers.
*   **Cluster 2 (High-Value Spenders)**: Customers with high annual income and high spending scores. They are the most valuable customers, ideal for premium offerings and loyalty programs.
*   **Cluster 3 (Impulse Buyers / Young Adults)**: Customers with lower annual income but high spending scores, possibly prone to impulse purchases or younger demographics. They could be targeted with trendy or value-for-money products.
*   **Cluster 4 (Careful High Earners)**: Customers with high annual income but low spending scores, suggesting careful expenditure. Marketing could focus on long-term value, quality, or investment products.
*   **Cluster 5 (Budget-Conscious)**: Customers with both low annual income and low spending scores, indicating a strong focus on budget. Promotions, discounts, and essential goods would appeal to this segment.

### Conclusion
This customer segmentation provides valuable insights for businesses to tailor their marketing strategies, product offerings, and customer service initiatives to better meet the needs and preferences of each distinct customer group, ultimately leading to improved customer satisfaction and business growth.
