# Customer Segmentation Using K-Means Clustering

## Problem Statement
This project performs customer segmentation based on demographic and spending data. By applying K-Means clustering, the aim is to group customers into different segments to help businesses understand their customer base and tailor marketing strategies effectively.

## Dataset
- **Mall_Customers.csv**: The dataset includes customer demographic information, including Age, Gender, Annual Income, and Spending Score. 
  - Maximum age: 70
  - Minimum age: 18
  - Average income: $60K

## Libraries Used
- `pandas`: For data manipulation and exploration.
- `numpy`: For numerical operations.
- `matplotlib` and `seaborn`: For data visualization.
- `scikit-learn`: For K-Means clustering and preprocessing.

## Methodology
1. **Data Exploration**:
   - Visualized the distribution of age, gender, and annual income.
   - Analyzed customer spending score and demographic information.

2. **Preprocessing**:
   - Encoded the Gender column into numerical values.
   - Dropped unnecessary columns like `CustomerID` for clustering.

3. **K-Means Clustering**:
   - Used the Elbow Method to determine the optimal number of clusters (6 clusters were chosen).
   - Applied K-Means algorithm to segment the customers.
   - Added the cluster assignments back to the dataset for further analysis.

## Results
- The final dataset contains an additional column `Cluster`, which indicates the cluster assignment of each customer.
- The cluster centers provide insights into the characteristics of each customer segment.

## How to Run
1. Load the dataset.
2. Run the K-Means clustering algorithm using the provided code.
3. Visualize the clusters and their characteristics.

