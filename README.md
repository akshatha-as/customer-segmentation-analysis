# Customer Segmentation Analysis (Python)

This project performs an end-to-end customer segmentation analysis using **Python**, focusing on understanding customer behavior based on **Annual Income**, **Spending Score**, and **Age**. The goal is to identify meaningful customer groups that support targeted marketing and data-driven business decisions.

---

## 🚀 Project Overview

- Conducted detailed **Exploratory Data Analysis (EDA)** to understand customer demographics and spending patterns.
- Applied **basic KMeans clustering** to segment customers into natural groups.
- Used the **Elbow Method** to determine the optimal number of clusters.
- Analyzed segment characteristics using group-wise statistics and visualizations.
- Derived actionable insights to identify high-value, low-value, and potential upsell customer groups.

---

## 🛠️ Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-Learn  

---

## 📂 Project Structure

Customer_Segmentation/
│── Customer_segmentation.ipynb    # Main analysis notebook
│── README.md                      # Project documentation
│── dataset.csv                    # Input dataset




---

## 🔍 Key Steps in the Analysis

### **1. Exploratory Data Analysis**
- Checked data types, missing values, and statistical summaries.
- Plotted distributions for income and spending score.
- Explored relationships using scatter plots and box plots.

### **2. Feature Selection**
Used three key behavioral features:
- **Annual Income (k$)**
- **Spending Score (1–100)**
- **Age**

### **3. Standardization**
- Applied **StandardScaler** to bring all numerical features onto a comparable scale.

### **4. Choosing Optimal Clusters**
- Tested k-values from 1 to 10.
- Used **Inertia** and plotted the **Elbow Curve** to identify the best k value.

### **5. Clustering**
- Ran **KMeans** clustering with the chosen number of clusters.
- Added cluster labels to the dataset.
- Profiled each segment using `groupby()` and descriptive statistics.

### **6. Interpretation**
Built clear segment interpretations such as:
- **High-Income High-Spend**
- **High-Income Low-Spend**
- **Low-Income Low-Spend**
- **Young High-Spend**
- **Average-Income High-Spend**

---

## 📊 Visualizations

The project includes:
- Distribution plots  
- Scatter plots  
- Box plots  
- Elbow curve  
- Cluster visualization graphs  

These help in interpreting customer behavior and segment boundaries.

---

## 🎯 Business Insights

- Identified high-value customer groups for premium targeting.
- Found high-income low-spend customers with upsell potential.
- Recognized low-spending groups for retention strategies.
- Provided a data-driven basis for marketing and personalization efforts.

---

🤝 Contributions

Contributions, issues, and suggestions are always welcome!
