<h1 align="center"> From Data to Design: Customer Segmentation for Myntra's Fashion Retail Strategy </h1>

<p align="center"> 
<img src="GIF/google play.gif" alt="Animated gif" height="282px">
</p>


## 📚 Table Of Contents

- 📋 **Project Description**
- 💾 **Project Files Description**
- 🧾 **Dataset Contents**
- 📊 **Variable Details Of Dataset**
- ❓ **Problem Statement**
- 🛠 **Technologies Used**
- 🔍 **Steps Involved**
- 📌 **Key Insights**
- 📋 **Conclusion**

## 📋 Project Description
The primary objective of this project was to harness the power of unsupervised learning to segment customers based on purchasing behavior from Myntra's vast transaction dataset. With over 500,000 transactions, the aim was to uncover hidden patterns, empower data-driven decision-making, and enhance personalized customer experiences.

Through detailed preprocessing, feature engineering, and model evaluation, the project provides a blueprint for how fashion retailers can better understand customer profiles and strategically align their marketing, product offerings, and operational strategies.

********************************************************************************************************************************************************************

##  💾 Project Files Description
This repository includes the following files:
- Jupyter Notebook: Contains code for data cleaning, exploratory data analysis, feature engineering, clustering model implementation (KMeans, Hierarchical, DBSCAN), and model evaluation.
- Dataset File: Myntra transaction data in CSV format.
- Visualizations & Outputs: Graphs, plots, and evaluation metrics for customer segmentation.
- README.md: Detailed project documentation.

********************************************************************************************************************************************************************

## 🧾 Dataset Contents
The dataset comprises a single CSV file with 541,909 rows and 8 columns, representing historical transaction data from Myntra's platform.

********************************************************************************************************************************************************************

## 📊 Variable Details Of Dataset


| Variable                       | Description                                                                                                     |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------|
| InvoiceNo                      | Unique identifier for each transaction or invoice                                                               |
| StockCode                      | Unique code for each product                                                                                    |
| Description                    | Name or description of the product                                                                              |
| Quantity                       | Number of units purchased                                                                                       |
| InvoiceDate                    | Date and time of the transaction                                                                                |
| UnitPrice                      | Price per unit of the product                                                                                   |
| CustomerID                     | Unique customer identifier                                                                                      |
| Country                        | Country from which the purchase was made                                                                        |

********************************************************************************************************************************************************************

## ❓ Problem Statement

In the competitive world of fashion e-commerce, understanding customer behavior is essential for crafting personalized experiences and improving retention. Myntra collects massive volumes of transaction data but lacks clear visibility into diverse customer segments.

This project aims to apply unsupervised machine learning to cluster customers based on purchasing behavior, enabling Myntra to deliver targeted marketing, optimize resources, and drive sustainable growth.

********************************************************************************************************************************************************************

## 🛠 Technologies Used

- Programming Language: Python

- Libraries:
    - pandas, numpy, datetime
    - matplotlib, seaborn, wordcloud
    - scikit-learn, scipy, yellowbrick
- Clustering Models:
    - KMeans
    - Agglomerative Clustering
    - DBSCAN
- Evaluation Metrics:
    - Silhouette Score

********************************************************************************************************************************************************************

## 🔍 Steps Involved

1. Data Cleaning & Preprocessing
 - Handled 136,534 missing values and removed 5,268 duplicates.
 - Filtered out invalid transactions (negative/zero quantity or price).

2. Data Type Conversion
 - Converted InvoiceDate to datetime and CustomerID to string.

3. Feature Engineering
 - Created TotalAmount, Recency, Frequency, Monetary, TenureDays, OrderRate, and AvgOrderValue.

4. Dimensionality Reduction
 - Applied PCA for visualization and efficiency.

5. Modeling
 - Implemented and compared KMeans, Agglomerative Clustering, and DBSCAN.
 - Tuned DBSCAN parameters using k-distance graph.

6. Evaluation
 - Silhouette Score used to assess cluster cohesion and separation.

********************************************************************************************************************************************************************

## 📌 Key Insights

- DBSCAN emerged as the best clustering model with a Silhouette Score of 0.638, indicating strong, well-separated customer segments.
- Segmentation revealed distinct customer profiles that vary in spending, frequency, and loyalty.
- High-value segments were identified for targeted promotions and loyalty programs.
- Segment-specific behaviors can inform marketing, inventory planning, and personalization strategies.

********************************************************************************************************************************************************************

## 📋 Conclusion:

This project demonstrates the power of unsupervised learning in customer segmentation. By identifying hidden patterns in Myntra's transaction data, the project:

- Enables precision marketing through customer-specific campaigns.
- Supports personalized product recommendations based on past behavior.
- Enhances operational efficiency by aligning resources with profitable segments.
- Lays the foundation for future strategies like predictive modeling and real-time personalization.

With these insights, Myntra can make smarter decisions, build deeper customer relationships, and maintain a competitive edge in the fashion retail landscape





