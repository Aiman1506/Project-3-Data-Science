# Project-3-Data-Science
# 🧠 Customer Lifestyle Clustering using K-Means

## 👩‍💻 Developed by: Umme Aiman Lalkot  
*B.Tech | Data Science Enthusiast | Python | Machine Learning*

---

## 📌 Overview

This project focuses on **Customer Segmentation** using **K-Means Clustering**, a popular unsupervised machine learning technique.  
It uses a shopping mall dataset to identify distinct customer groups based on **Annual Income** and **Spending Score**.

---

## 📊 Dataset Information

The dataset used contains the following columns:

- `CustomerID` – Unique ID of each customer  
- `Gender` – Male/Female  
- `Age` – Customer age  
- `Annual Income (k$)` – Annual income in thousands of dollars  
- `Spending Score (1–100)` – Score assigned by the mall based on customer behavior

---

## 🧪 Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn (KMeans)  
- Jupyter Notebook

---

## 🔍 Project Workflow

1. **Data Preprocessing**
   - Loaded the dataset
   - Checked for missing values
   - Selected important features (`Annual Income`, `Spending Score`) for clustering

2. **K-Means Clustering**
   - Chose `k=5` clusters using the KMeans algorithm
   - Used the `k-means++` initialization method for efficient clustering
   - Assigned each customer a cluster label

3. **Visualization**
   - Used a scatter plot to visualize clusters
   - Each cluster is shown with a different color
   - Cluster centroids are highlighted with black 'X' markers

---

## 📈 Output Plot

The final visualization shows customer segments based on their income and spending patterns.  
This helps businesses target marketing strategies for high-value or low-engagement groups.

---

## 📦 How to Run

1. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Run the Jupyter Notebook:

```bash
jupyter notebook Project\ 3.ipynb
```

3. Observe the clustering visualization and interpretation.

---

## 🧠 Insights

- High-income, low-spending customers may need targeted offers.  
- Moderate spenders with mid-level income form the largest cluster.  
- Grouping helps in personalized marketing and resource optimization.

---

## 📬 Contact

For queries or collaborations:  
**Umme Aiman Lalkot**  
Email: [ummeaiman1506@gmail.com]  

---

## 🏁 Conclusion

K-Means clustering effectively groups mall customers based on behavior, aiding in strategic decision-making for business growth.
