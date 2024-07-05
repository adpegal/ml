
# Data Science Project: Customer Segmentation

## Project Overview

This project aims to segment customers based on their demographic and transaction data using KMeans clustering. The goal is to identify distinct customer groups to better understand their characteristics and tailor marketing strategies accordingly.

## Data Description

The dataset contains the following columns:
- `customer_id`: Unique identifier for each customer
- `age`: Age of the customer
- `gender`: Gender of the customer
- `dependent_count`: Number of dependents the customer has
- `education_level`: Educational background of the customer
- `marital_status`: Marital status of the customer
- `estimated_income`: Estimated yearly income of the customer
- `months_on_book`: time as a customer in months
- `total_relationship_count`: number of times the customer was in touch with the company
- `months_inactive_12_mon`: Number of months the customer has been inactive in the last 12 months
- `credit_limit`: Credit limit of the customer
- `total_trans_amount`: Total transaction amount
- `total_trans_count`: Total number of transactions
- `avg_utilization_ratio`: Average utilization ratio of the credit limit
- `cluster`: Cluster assignment of the customer (output of the project)

## Methodology

1. **Data Preprocessing**: Cleaned the dataset and handled any missing values.
2. **Feature Selection**: Selected relevant features for clustering.
3. **KMeans Clustering**: Applied KMeans clustering to segment customers.
4. **Elbow Method**: Used the elbow method to determine the optimal number of clusters.
5. **Principal Component Analysis (PCA)**: Reduced dimensionality using PCA for visualization purposes.
6. **Cluster Analysis**: Analyzed the characteristics of each cluster and proposed meaningful names.

## Clusters Analysis

### 1. Young Professionals
   * **Age**: ~35 years
   * **Dependent Count**: ~1.5
   * **Estimated Income**: ~\$55,000
   * **Months on book**: ~26
   * **Credit Limit**: ~\$5,460
   * **Total Transactions**: ~57
   * **Utilization Ratio**: ~0.31
   * **Characteristics**: Relatively young with moderate income and credit limit, actively using credit.

### 2. Moderate Income Middle-Aged
   * **Age**: ~46 years
   * **Dependent Count**: ~2.9
   * **Estimated Income**: ~\$41,000
   * **Months on book**: ~36
   * **Credit Limit**: ~\$2,641
   * **Total Transactions**: ~70
   * **Utilization Ratio**: ~0.64
   * **Characteristics**: Middle-aged with moderate income, high utilization ratio, and moderate transaction activity.
   * **Mostly Female customers**

### 3. Wealthy Middle-Aged
   * **Age**: ~47 years
   * **Dependent Count**: ~2.6
   * **Estimated Income**: ~\$119,000
   * **Months on book**: ~37
   * **Credit Limit**: ~\$22,511
   * **Total Transactions**: ~58
   * **Utilization Ratio**: ~0.07
   * **Characteristics**: High income and credit limit, low utilization ratio, middle-aged with moderate transactions.
   * **Mostly Male customers**

### 4. High Spenders
   * **Age**: ~45 years
   * **Dependent Count**: ~2.3
   * **Estimated Income**: ~\$67,500
   * **Months on book**: ~35
   * **Credit Limit**: ~\$14,319
   * **Total Transactions**: ~105
   * **Utilization Ratio**: ~0.17
   * **Characteristics**: High transaction volume and credit limit, middle-aged, moderate utilization
   * **Slighlty more Male customers**

### 5. Senior Savers
   * **Age**: ~57 years
   * **Dependent Count**: ~1.1
   * **Estimated Income**: ~\$52,000
   * **Months on book**: ~45
   * **Credit Limit**: ~\$5,129
   * **Total Transactions**: ~54
   * **Utilization Ratio**: ~0.31
   * **Characteristics**: Older individuals with lower dependent count, moderate income, and savings behavior.

### 6. Family Focused
   * **Age**: ~45 years
   * **Dependent Count**: ~3.1
   * **Estimated Income**: ~\$49,000
   * **Months on book**: ~35
   * **Credit Limit**: ~\$6,298
   * **Total Transactions**: ~60
   * **Utilization Ratio**: ~0.10
   * **Characteristics**: Moderate income, larger families, moderate credit limit, and transaction volume.

## Conclusion

This customer segmentation project provides valuable insights into the different customer groups within the dataset. By understanding the characteristics of each cluster, businesses can tailor their strategies to better meet the needs of each segment, ultimately improving customer satisfaction and business performance.

