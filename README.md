# Customer Segmentation using K-Means Clustering and Principal Component Analysis (PCA)

## Objective

The objective of this project is to segment mall customers into distinct groups based on their demographic and spending behavior using the K-Means Clustering algorithm. Principal Component Analysis (PCA) is applied to reduce the dimensionality of the dataset and visualize the customer segments in two dimensions. This helps businesses better understand customer behavior and create targeted marketing strategies.

---

## Dataset

**Mall Customer Segmentation Dataset**

Kaggle: https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python

**Dataset Features**

* CustomerID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1–100)

---

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Scikit-learn

  * StandardScaler
  * KMeans
  * PCA

---

## Methodology

1. Loaded the customer segmentation dataset using Pandas.
2. Explored the dataset by viewing the first few records, checking data types, and generating summary statistics.
3. Checked for missing values and confirmed data quality.
4. Removed the **CustomerID** column as it does not contribute to clustering.
5. Encoded the **Gender** column into numerical values.
6. Standardized all numerical features using **StandardScaler**.
7. Applied the **Elbow Method** to determine the optimal number of clusters.
8. Trained the **K-Means Clustering** model using the selected number of clusters.
9. Assigned cluster labels to each customer.
10. Applied **Principal Component Analysis (PCA)** to reduce the dataset to two principal components.
11. Visualized the clusters using scatter plots and PCA projections.

---

## Results

* Successfully preprocessed and standardized the customer data.
* The Elbow Method indicated that **5** is the optimal number of clusters.
* K-Means grouped customers into five distinct segments based on income and spending behavior.
* PCA reduced the multidimensional dataset into two principal components while preserving most of the important information.
* The resulting visualizations clearly displayed the separation between customer groups.

---

## Observations

1. The Elbow Curve showed a clear bend at **K = 5**, indicating that five clusters provide an effective balance between model simplicity and clustering performance.

2. PCA successfully reduced the multidimensional dataset into two principal components, making it easier to visualize customer groups while retaining most of the data variance.

3. The identified clusters represent customers with different spending patterns and income levels, such as high-income/high-spending customers, high-income/low-spending customers, average-income customers, and lower-income customer groups. These segments can be used to design personalized marketing campaigns and improve business decision-making.

---

## Conclusion

This project successfully demonstrated customer segmentation using K-Means Clustering and Principal Component Analysis (PCA). The Elbow Method identified five as the optimal number of clusters, enabling meaningful grouping of customers based on demographic and purchasing behavior. PCA simplified the high-dimensional data into two principal components, making the clusters easier to interpret and visualize. Customer segmentation helps businesses develop targeted marketing strategies, improve customer satisfaction, and optimize promotional campaigns. A limitation of K-Means is that the number of clusters must be specified before training, and the algorithm is sensitive to outliers and initial centroid selection. An important advantage of PCA is its ability to reduce dimensionality while preserving most of the essential information, resulting in easier analysis and better visualization of complex datasets.
# Customer-Segmentation-using-K-Means-and-PCA
