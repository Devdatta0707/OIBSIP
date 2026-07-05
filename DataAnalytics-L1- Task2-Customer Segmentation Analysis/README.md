Task 2 : Customer Segmentation Analysis using KMeans Clustering

 Objective
The objective of this project is to apply clustering algorithms to segment an e-commerce company's customers into different groups based on purchasing behavior. This helps businesses improve marketing strategies, customer retention, and revenue generation.



 Tech Stack
- Python
- pandas
- NumPy
- scikit-learn
- matplotlib
- seaborn
- Jupyter Notebook



 Dataset
Dataset Used: SuperStore Orders Dataset

The dataset contains:
- Customer information
- Order details
- Sales data
- Product details
- Shipping information



 Project Workflow

 1. Data Loading and Inspection
- Loaded dataset using pandas
- Inspected shape, columns, and datatypes
- Checked missing values

 2. Data Cleaning
- Cleaned column names
- Handled missing values
- Converted date columns into datetime format

 3. Descriptive Statistics
Calculated:
- Average Purchase Value
- Purchase Frequency
- Customer Lifetime Value



 RFM Analysis

RFM stands for:

- Recency → How recently a customer purchased
- Frequency → How often the customer purchases
- Monetary → How much money the customer spends

RFM features were created for customer segmentation.



 Data Standardization
Used `StandardScaler` to normalize:
- Recency
- Frequency
- Monetary

This improves clustering performance.



KMeans Clustering
Applied KMeans clustering algorithm to group customers into segments.

Elbow Method
Used the Elbow Method to determine the optimal number of clusters.



 Visualizations
The following visualizations were created:
- Elbow Method Graph
- Frequency vs Monetary Scatter Plot
- Recency vs Monetary Scatter Plot
- Customer Cluster Bar Chart
- Cluster Heatmap


 Customer Segments

 Cluster 0
- High-value customers
- Loyal and frequent buyers

 Recommendation
- Premium membership
- Exclusive discounts



 Cluster 1
- Low frequency customers

 Recommendation
- Promotional emails
- Discount campaigns



 Cluster 2
- Recently active customers

 Recommendation
- Loyalty rewards
- Product recommendations



 Cluster 3
- At-risk customers

 Recommendation
- Re-engagement campaigns
- Personalized offers



 Conclusion
Customer segmentation using RFM analysis and KMeans clustering helps businesses:
- Understand customer behavior
- Improve targeted marketing
- Increase customer retention
- Maximize business revenue







