# 🧑‍🤝‍🧑 Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project performs **customer segmentation** using the **K-Means clustering algorithm** on the Mall Customers dataset. The objective is to group customers based on their **annual income** and **spending behavior**, enabling businesses to better understand customer patterns and target them effectively.

---

## 📂 Dataset Description
- **Dataset Name:** Mall_Customers.csv  
- **Records:** Customer purchase data  
- **Key Attributes Used:**
  - Annual Income (k$)
  - Spending Score (1–99)

Other attributes such as `CustomerID`, `Age`, and `Genre` are removed for clustering purposes.

---

## ⚙️ Technologies & Libraries Used
- **Python**
- **Pandas** – Data handling
- **NumPy** – Numerical computation
- **Scikit-learn** – K-Means clustering
- **Matplotlib** – Data visualization

---

## 🔄 Data Preprocessing
- Checked for null values
- Encoded categorical column **Genre** using Label Encoding
- Selected relevant numerical features
- Removed unnecessary columns to improve clustering accuracy

---

## 📐 Elbow Method for Optimal Clusters
The **Elbow Method** is used to determine the optimal number of clusters by plotting:
- Number of clusters (K)
- Within-Cluster Sum of Squares (WCSS)

From the elbow curve, **K = 5** is chosen as the optimal number of clusters.

---

## 🧠 K-Means Clustering
- **Algorithm:** K-Means
- **Number of Clusters:** 5
- **Initialization:** k-means++
- **Random State:** 42

The model assigns each customer to a cluster based on similarity in income and spending behavior.

---

## 📊 Visualization
- Scatter plot is used to visualize clusters
- Each cluster is represented using a different color
- Clear labeling of axes and legend for interpretation

---

## 📈 Applications
- Customer segmentation for targeted marketing
- Personalized offers and recommendations
- Understanding high-value and low-value customers
- Business strategy optimization

---

## ✅ Conclusion
This project demonstrates how unsupervised learning techniques like **K-Means clustering** can uncover meaningful customer segments. The insights gained can help businesses improve customer engagement and profitability.

---

## 🚀 Future Enhancements
- Adding customer demographics for deeper insights
- Trying other clustering algorithms (DBSCAN, Hierarchical)
- Cluster profiling and interpretation
- Integrating results into dashboards
