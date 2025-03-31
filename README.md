# 🛍️ Customer Segmentation Using Clustering & Correlation Analysis

## 📖 Project Overview
This project analyzes buying behavior of customers through the aid of **K-Means clustering** and **correlation analysis**. It tries to segment customers into categories based on spending, purchase frequency, and recency. Organizations utilize these results to **Determine high-value customers, optimize marketing, and improve customer retention**.

## 📊 Dataset Information
- **Dataset Name:** `online_sales_dataset.csv`
- **Data Attributes:**  
  - `CustomerID`: Unique ID for each customer  
  - `PurchaseDate`: Date of purchase  
  - `Quantity`: Number of items purchased  
  - `UnitPrice`: Price per item  
  - `TotalSpend`: Computed as `Quantity * UnitPrice`  
  - `Recency`: Days since last purchase  

## 🚀 Methodology
1. **Data Cleaning & Preprocessing**
   - Handled missing values and outliers.
   - Converted date columns to the appropriate format.
   - Scaled numerical data for clustering.

2. **Customer Segmentation Using K-Means**
   - Applied the **K-Means clustering algorithm** to group customers.
   - Determined the optimal number of clusters using the **Elbow Method** & **Silhouette Score**.

3. **Correlation Analysis**
   - Identified relationships between customer spending, frequency, and recency.
   - Used correlation heatmaps for better insights.

4. **Data Visualization**
   - Scatter plots for cluster distribution.
   - Bar charts and histograms for spending behavior.

## 📈 Key Findings & Insights
- Identified **high-value customers** who buy regularly.
- Identified the **customer segments** based on spending behavior.
- Suggested business plans for **targeting multiple customer segments**.

## 🛠️ Technologies Used
- **Programming Language:** R  
- **Libraries:** `dplyr`, `ggplot2`, `corrplot`, `reshape2`

## 🔧 How to Use the Project
1. Clone the repository:
   ```bash
   https://github.com/AYUSH0613/Customer-Segmentation-Analysis.git
