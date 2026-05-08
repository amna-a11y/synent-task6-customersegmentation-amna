Task 6 – Customer Segmentation Using K-Means Clustering
Problem Statement

Businesses often struggle to understand different types of customers and their purchasing behavior. Without proper analysis, marketing strategies become inefficient and less targeted. This project uses machine learning (K-Means clustering) to group customers into meaningful segments based on their sales behavior, helping businesses improve targeting and increase profitability.

Dataset Details
Dataset Name: Superstore / Customer Sales Dataset
Format: CSV (or extracted from ZIP file)
Key Feature Used: Sales
Optional Features: Quantity, Discount, Profit, Customer ID
Approach
1. Data Preprocessing
Dataset uploaded in CSV or ZIP format
Extracted and cleaned data
Selected relevant numerical features (Sales or Income, Spending Score)
Handled missing values
2. Feature Scaling
Applied StandardScaler for normalization
Standardized data to improve clustering performance
3. Finding Optimal Clusters (Elbow Method)
Used WCSS (Within-Cluster Sum of Squares)
Plotted Elbow curve
Optimal number of clusters selected as K = 3
4. K-Means Clustering
Applied K-Means algorithm
Grouped customers into segments:
Low-value customers
Medium-value customers
High-value customers
5. Visualization
Elbow Method graph
Customer cluster scatter plot
Cluster-wise analysis
Code Overview
Libraries Used
pandas
numpy
matplotlib
scikit-learn
PIL (for report image generation)
Main Steps
Data loading using Pandas
Feature scaling using StandardScaler
Elbow method for optimal K selection
K-Means clustering implementation
Cluster visualization using scatter plot
Report generation and export
Results
Customer Segments Identified
High-value customers: High income and high spending
Medium-value customers: Average income and spending
Low-value customers: Low income or low spending
Key Insights
High-value customers contribute most revenue and should be prioritized
Medium-value customers can be converted into high-value through marketing strategies
Low-value customers can be targeted with discounts and engagement campaigns
Elbow method confirms optimal clustering at K = 3
Feature scaling is essential for accurate clustering results
Output Files
elbow_method.png
customer_clusters.png
Customer_Report.png
Final_Output.zip
Conclusion

This project successfully applies K-Means clustering to segment customers based on behavior. The results help businesses design better marketing strategies, improve customer targeting, and increase overall profitability.
