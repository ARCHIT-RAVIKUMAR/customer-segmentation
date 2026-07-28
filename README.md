# Customer Segmentation using K-Means Clustering

**Participant Name:** Archit Ravikumar  
**MUID:** architravikumar@mulearn

---

## Project Summary

This project applies the K-Means Clustering algorithm to segment mall customers based on their demographic information and spending behavior. Principal Component Analysis (PCA) is used to visualize the generated customer segments and identify meaningful business patterns.

---

## Business Objective

The objective of this project is to group customers into similar segments so that businesses can better understand customer behavior and design targeted marketing strategies for each customer group.

---

## Dataset Overview

The dataset contains **200 customer records** with the following features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Approach

The following steps were performed:

- Loaded and explored the dataset
- Checked for missing values and duplicate records
- Encoded the Gender column
- Removed the CustomerID column since it is only an identifier
- Applied StandardScaler for feature scaling
- Used the Elbow Method to determine the optimal number of clusters
- Trained a K-Means clustering model with 5 clusters
- Applied PCA for two-dimensional visualization
- Analyzed each customer segment and generated business insights

---

## Important Findings

- The Elbow Method suggested **5 clusters** as the optimal number of customer segments.
- Customers were successfully grouped into five meaningful clusters based on their characteristics.
- PCA reduced the dataset into two principal components for visualization.

### PCA Variance Explained

| Component | Variance Explained |
|-----------|------------------:|
| PC1 | 33.69% |
| PC2 | 26.23% |
| **Total** | **59.92%** |

---

## Cluster Summary

| Customer Segment | Average Age | Average Income (k$) | Average Spending Score |
|-------------------------|------------:|--------------------:|-----------------------:|
| Premium Customers | 32.69 | 86.54 | 82.13 |
| Careful High-Income Customers | 36.48 | 89.52 | 18.00 |
| Budget-Conscious Adults | 49.81 | 49.23 | 40.07 |
| Young Active Shoppers | 24.91 | 39.72 | 61.20 |
| Senior Moderate Spenders | 55.71 | 53.69 | 36.77 |

---

## Business Insights

### Premium Customers
These customers have high income and high spending behavior. They are valuable customers who should be retained through loyalty programs and exclusive offers.

### Careful High-Income Customers
These customers have high purchasing power but spend less. Personalized promotions and premium product recommendations may encourage higher spending.

### Budget-Conscious Adults
These customers have moderate income and relatively lower spending. Discounts and value-based offers can improve customer engagement.

### Young Active Shoppers
These customers are younger and spend actively despite having comparatively lower income. Trend-based marketing campaigns and seasonal offers can help retain them.

### Senior Moderate Spenders
These customers have moderate spending habits and stable purchasing behavior. Providing quality service and personalized communication can strengthen customer loyalty.

---

## Conclusion

This project successfully segmented mall customers into five meaningful groups using K-Means Clustering. The Elbow Method helped determine the optimal number of clusters, while PCA provided an effective visualization of the customer segments. These insights can help businesses design targeted marketing strategies, improve customer satisfaction, and make better data-driven business decisions.
