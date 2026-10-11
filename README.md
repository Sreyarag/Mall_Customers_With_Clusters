# Mall Customer Segmentation Using K-Means Clustering

## 📌 Project Overview

This project uses **K-Means Clustering**, an unsupervised machine learning algorithm, to group mall customers based on their annual income and spending scores.

The goal is to identify different customer segments and understand their spending behavior.

## 🎯 Objectives

* Analyze customer data using Exploratory Data Analysis (EDA).
* Visualize customer income and spending patterns.
* Use the Elbow Method to determine the number of clusters.
* Apply K-Means Clustering to group customers into five clusters.
* Interpret the characteristics of each customer segment.

## 📊 Dataset

The project uses the Mall Customers dataset, which contains 200 customer records.

The dataset includes the following columns:

* `CustomerID` — Unique customer identifier.
* `Gender` — Customer gender.
* `Age` — Customer age.
* `Annual Income (k$)` — Annual income in thousands of dollars.
* `Spending Score (1-100)` — Spending score assigned to each customer.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

## ⚙️ Project Workflow

1. Load and explore the dataset.
2. Check missing values and duplicate records.
3. Perform Exploratory Data Analysis (EDA).
4. Select annual income and spending score as features.
5. Scale the features using StandardScaler.
6. Apply the Elbow Method to select the number of clusters.
7. Train the K-Means model with five clusters.
8. Visualize and interpret the customer segments.
9. Save the dataset with cluster labels.

## 📈 Customer Segments

The model identified five customer clusters:

* **Cluster 0:** Middle-income customers with average spending scores.
* **Cluster 1:** High-income customers with high spending scores.
* **Cluster 2:** Lower-income customers with high spending scores.
* **Cluster 3:** High-income customers with low spending scores.
* **Cluster 4:** Lower-income customers with low spending scores.

These descriptions are based on the average income and spending scores of each cluster.

## 📁 Project Files

* `mall_customer_segmentation.ipynb` — Jupyter notebook containing the analysis and model.
* `Mall_Customers.csv` — Original dataset.
* `Mall_Customers_With_Clusters.csv` — Dataset containing the assigned cluster labels.

## 🚀 How to Run

1. Clone or download this repository.
2. Open `mall_customer_segmentation.ipynb` in Google Colab or Jupyter Notebook.
3. Upload `Mall_Customers.csv` to your working environment.
4. Run the notebook cells in order.
5. View the visualizations and customer clusters.

## 💡 Conclusion

K-Means Clustering helps identify customer groups with similar income and spending patterns. This information can help businesses understand their customers and plan more targeted marketing strategies.

## 👩‍💻 Author

Created as a beginner machine learning project to practice Python, data analysis, and unsupervised learning.
