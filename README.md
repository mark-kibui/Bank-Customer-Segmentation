# Bank Customer Segmentation

This project focuses on segmenting bank customers to identify distinct groups based on their characteristics and behavior. The goal is to enable the bank to tailor marketing strategies, products, and services more effectively to each customer group.

## Project Overview

Customer segmentation helps businesses, like banks, identify patterns in customer behavior, allowing for more personalized and targeted services. In this project, we use clustering techniques to segment customers and improve business decision-making.

### Objectives:
- Segment bank customers into distinct groups.
- Provide insights into the characteristics of each group.
- Use clustering techniques to drive marketing and business strategies.

## Dataset

The dataset contains various customer attributes, such as:
- **Demographics**: Age and gender
- **Behavioral Data**: Account usage such as transaction patters.

## Methodology

### 1. Data Preprocessing
- Cleaning missing values.
- Encoding categorical variables.
- Normalizing or scaling numerical features for clustering.

### 2. Feature Engineering
- Selected features based on domain knowledge.
- Created new features or transformed existing ones for better clustering results.

### 3. Clustering Model: K-means
- Used **K-means clustering** to segment customers.
- **Elbow Method**: Applied to determine the optimal number of clusters by plotting the within-cluster sum of squares (WSS) against the number of clusters.
- **Silhouette Score**: Calculated to evaluate the quality of the clusters. A higher silhouette score indicates better-defined clusters, with greater separation between groups.

## Results

The K-means algorithm provided clusters of customers, each with unique characteristics. By analyzing these segments, the bank can tailor its marketing efforts and product offerings more effectively.

### Cluster Profiles:
- Profile of each cluster with key customer characteristics.
- Insights into customer behavior within each segment.

## Next Steps

- Refine the clustering model with alternative techniques if necessary (e.g., DBSCAN, hierarchical clustering).
- Validate the segments against business objectives and customer data.
- Deploy the segmentation model for operational use by the bank.

## Requirements

- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `scikit-learn`, `seaborn`

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/mark-kibui/Bank-Customer-Segmentation.git
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the main script to perform clustering:
    ```bash
    python segmentation.py
    ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

