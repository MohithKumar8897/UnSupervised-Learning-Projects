# 💳 Credit Card Customer Segmentation using Unsupervised Learning

This project aims to segment credit card customers based on their spending patterns using unsupervised learning techniques, primarily K-Means Clustering. By identifying customer groups, financial institutions can tailor personalized marketing strategies and improve customer relationship management.

## 📁 Dataset Description

**File:** `CC GENERAL.csv`  
This dataset contains behavioral data for approximately 8,950 credit card customers, with features such as:

- `BALANCE`: Monthly average balance
- `PURCHASES`: Amount of purchases
- `CREDIT_LIMIT`: Assigned credit limit
- `TENURE`: Duration of the relationship with the customer
- `PAYMENTS`, `PRC_FULL_PAYMENT`, `INSTALLMENTS_PURCHASES`, etc.

Missing values are handled, and all variables are scaled for better model performance.

## 🧠 Project Workflow

**Notebook:** `Credit Card Clustering using Python.ipynb`  
The complete analysis is performed in a Jupyter notebook, covering:

### 1. Data Preprocessing
- Checking null values
- Filling missing values with the mean
- Feature selection for clustering
- Scaling data using `StandardScaler`

### 2. Exploratory Data Analysis (EDA)
- Distribution plots
- Correlation heatmap

### 3. Clustering
- Using the Elbow Method to find optimal clusters
- Applying KMeans Clustering
- Principal Component Analysis (PCA) for dimensionality reduction
- 2D/3D visualization of clusters

### 4. Cluster Interpretation
- Each cluster is profiled based on customer behaviors
- Business insights derived for each group

## 📊 Key Techniques Used

- **Unsupervised Learning**: K-Means, PCA
- **Visualization**: Seaborn, Matplotlib, Plotly
- **Evaluation**: Silhouette Score, Inertia (WCSS)

## 🛠️ Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn / Plotly
- Scikit-learn

## 📌 How to Run
