# Customer Segmentation using K-Means

## 📌 Project Overview
This project applies **K-Means clustering** to segment customers into different groups based on their **Annual Income** and **Spending Score**.  
The insights from this project can help businesses identify **high-value customers**, **budget customers**, and create **personalized marketing strategies**.

## 🗂️ Dataset
- Dataset: `Mall_Customers.csv`
- Columns:  
  - `CustomerID` – Unique ID for each customer  
  - `Age` – Customer’s age  
  - `Gender` – Male/Female  
  - `Annual Income (k$)` – Income of customer in $1000  
  - `Spending Score (1–100)` – Score assigned by the mall based on spending behavior  

Dataset source: [Mall Customers Dataset (Kaggle)](https://www.kaggle.com/datasets/shwetabh123/mall-customers)

## 🛠️ Tools & Libraries
- Python (Pandas, Numpy, Matplotlib, Seaborn, Scikit-learn)
- Jupyter Notebook

## 🚀 Steps in the Project
1. **Data Exploration** → Understanding customer demographics.  
2. **Data Cleaning** → Checking for missing values.  
3. **EDA** → Visualizing spending vs income.  
4. **Feature Scaling** → Standardizing data for K-Means.  
5. **Modeling** → Applying K-Means clustering.  
6. **Evaluation** → Using Elbow Method to find optimal clusters.  
7. **Visualization** → Scatter plots of clusters.  

## 📊 Results / Insights
- **Cluster 0** → High income, high spending (Premium customers)  
- **Cluster 1** → Low income, low spending (Budget customers)  
- **Cluster 2** → High income, low spending (Careful spenders)  
- **Cluster 3** → Moderate income, high spending (Potential loyal customers)  

## 📂 Files in this Repo
- `Customer_Segmentation_KMeans.ipynb` → Jupyter Notebook with full project code.  
- `Mall_Customers.csv` → Dataset used.  
- `README.md` → Project documentation.  

## 📸 Sample Output
*(You can add screenshots of cluster plots here after running the notebook)*

---

### ✅ How to Run
1. Clone this repo or download the files.  
2. Open `Customer_Segmentation_KMeans.ipynb` in Jupyter Notebook.  
3. Make sure `Mall_Customers.csv` is in the same folder.  
4. Run all cells to reproduce the results.
