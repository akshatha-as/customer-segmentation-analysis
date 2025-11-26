📌 Customer Segmentation Analysis (Python)

This project performs an end-to-end customer segmentation analysis using Python, focusing on understanding customer behavior based on Annual Income, Spending Score, and Age.
The primary goal is to identify meaningful customer groups that can support targeted marketing and business decision-making.

🚀 Project Overview

Conducted Exploratory Data Analysis (EDA) to understand customer demographics and spending patterns.

Applied basic KMeans clustering to identify natural customer groups.

Used the Elbow Method to determine the optimal number of clusters.

Analysed segment characteristics using statistical summaries and visualizations.

Derived actionable insights for identifying high-value, low-value, and potential upsell customer groups.

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

📂 Project Structure
Customer_Segmentation/
│── Customer_segmentation.ipynb    # Main analysis notebook
│── README.md                      # Project documentation
│── dataset.csv (optional)         # Mall customers dataset

🔍 Key Steps in the Analysis
1. Data Exploration

Checked data types, missing values, and summary statistics.

Visualized distributions for Annual Income and Spending Score.

Analysed relationships using scatter plots and box plots.

2. Feature Selection

Used the following features for segmentation:

Annual Income (k$)

Spending Score (1–100)

Age

3. Standardization

Applied StandardScaler to bring all numerical features to a similar scale.

4. Determining Optimal Clusters

Tested cluster values from 1 to 10.

Plotted the Elbow Curve using inertia to identify the best k.

5. Clustering

Applied KMeans with the selected k.

Added cluster labels back to the dataset.

Profiled each segment using groupby().

6. Interpretation

Converted clusters into business-friendly groups such as:

High-Income High-Spend

High-Income Low-Spend

Low-Income Low-Spend

Young High-Spend

Average-Income High-Spend

📊 Visualizations Used

Distribution plots

Scatter plots

Box plots

Elbow curve

Cluster visualizations

These help understand segment boundaries and customer patterns.

🎯 Business Insights

Identified high-value segments for premium targeting.

Found potential upsell customers (high income, low spend).

Recognized low-engagement groups for retention planning.

Helped categorize customers based on purchasing behavior.

📘 How to Run the Project

Clone the repository:

git clone <repo-link>


Install dependencies:

pip install -r requirements.txt


Open the notebook:

jupyter notebook Customer_segmentation.ipynb

🤝 Contributions

Pull requests and suggestions are welcome!
