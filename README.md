# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project demonstrates customer segmentation using the **K-Means Clustering** algorithm, an unsupervised machine learning technique. The model groups customers based on their purchasing behavior to help businesses better understand different customer segments.

The dataset used is the **Mall Customers Dataset**, which contains customer demographic information and spending habits.

---

## 🎯 Objective

The objective of this project is to:

- Perform customer segmentation using K-Means clustering.
- Identify groups of customers with similar purchasing behavior.
- Visualize the customer clusters.
- Understand how businesses can use customer segmentation for targeted marketing.

---

## 📂 Dataset

**Dataset Name:** Mall Customers Dataset

### Features

| Feature | Description |
|---------|-------------|
| CustomerID | Unique customer ID |
| Gender | Male/Female |
| Age | Customer age |
| Annual Income (k$) | Annual income in thousand dollars |
| Spending Score (1-100) | Spending score assigned by the mall |

For clustering, the following features were used:

- Annual Income (k$)
- Spending Score (1-100)

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## 📊 Machine Learning Algorithm

**Algorithm:** K-Means Clustering

K-Means is an unsupervised learning algorithm that partitions data into **K clusters**, where each data point belongs to the cluster with the nearest centroid.

### Model Parameters

```python
KMeans(
    n_clusters=5,
    init='k-means++',
    max_iter=300,
    n_init=10,
    random_state=0
)
```

---

## 📈 Workflow

1. Load the dataset.
2. Explore and clean the data.
3. Select relevant features.
4. Apply the Elbow Method to determine the optimal number of clusters.
5. Train the K-Means model.
6. Predict customer clusters.
7. Visualize the clusters and centroids.

---

## 📉 Elbow Method

The Elbow Method was used to determine the optimal number of clusters by calculating the Within-Cluster Sum of Squares (WCSS) for different values of **K**.

The optimal number of clusters selected was:

**K = 5**

---

## 📊 Cluster Visualization

The trained model groups customers into five distinct clusters based on:

- Annual Income
- Spending Score

The cluster centroids represent the average characteristics of each customer group.

---

## 🚀 Installation

Clone this repository:

```bash
git clone https://github.com/your-username/customer-segmentation-kmeans.git
```

Navigate to the project directory:

```bash
cd customer-segmentation-kmeans
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Run the Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebook and execute all cells.

---

## 📁 Project Structure

```
Customer-Segmentation-KMeans/
│
├── Mall_Customers.csv
├── Customer_Segmentation.ipynb
├── README.md
├── requirements.txt
└── images/
    ├── elbow_method.png
    └── customer_clusters.png
```

---

## 📌 Results

The K-Means model successfully segmented customers into five meaningful groups based on their income and spending patterns.

These clusters can help businesses:

- Identify high-value customers
- Target marketing campaigns
- Improve customer retention
- Develop personalized promotional strategies

---

## 🔮 Future Improvements

- Compare K-Means with Hierarchical Clustering.
- Use additional customer features.
- Evaluate clustering performance using Silhouette Score.
- Deploy the model as a web application using Streamlit or Flask.

---

## 📚 Libraries

- pandas
- numpy
- matplotlib
- scikit-learn

Install them using:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## 👨‍💻 Author

**Adil Mushtaq**

GitHub: https://github.com/adilmushtaq67/K-Means-Clusters

---

## ⭐ If you found this project useful

Please consider giving this repository a **⭐ Star** on GitHub!
