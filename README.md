# eCommerce_Project
# EDA, Lookalike Model, and Clustering

##  Project Overview
This repository contains data-driven analyses and machine learning models to understand customer behavior. The project is divided into three key sections:  
1. **Exploratory Data Analysis (EDA)** – Analyzing customer transaction data to extract meaningful insights.  
2. **Lookalike Model** – Identifying similar customers based on behavioral and demographic attributes.  
3. **Clustering** – Segmenting customers into groups using K-Means clustering for better business strategies.  

---

##  1. Exploratory Data Analysis (EDA)
EDA involves visualizing and summarizing the dataset to uncover trends, patterns, and outliers.  

### **Key Steps:**
- Data Cleaning: Handling missing values, duplicates, and formatting issues.  
- Statistical Summary: Mean, median, standard deviation, etc.  
- Feature Analysis: Understanding key variables such as **purchase behavior, demographics, and spending trends**.  
- Visualizations:
  - Distribution plots of spending patterns.  
  - Correlation heatmaps to understand feature relationships.  
  - Time-series analysis of purchase frequency.  

### **Findings:**
- High-spending customers contribute significantly to total revenue.  
- Some customers make frequent small purchases, while others make rare but high-value purchases.  
- Spending behavior varies by region and customer demographics.  

---

##  2. Lookalike Model  
The Lookalike Model helps identify customers who share similar behaviors and characteristics with a target group (e.g., loyal customers or high spenders).  

### **Approach:**
1. **Feature Engineering**:  
   - Selected behavioral and demographic features such as total spending, purchase frequency, region, etc.  
2. **Scaling & Transformation**:  
   - Standardized numerical features to bring them to the same scale.  
3. **Model Training**:  
   - Used **cosine similarity** to group similar customers.  
4. **Evaluation**:  
   - Verified results by comparing clusters with known customer behaviors.  

### **Results & Insights:**
- The model successfully identified a segment of high-value potential customers.  
- Lookalike customers had **higher conversion rates** when targeted with similar marketing campaigns.  

---

##  3. Customer Clustering  
K-Means clustering was applied to segment customers based on their **transactional behavior**.  

### **Process:**
1. **Feature Selection**:  
   - Total spending, number of purchases, average purchase value, and total quantity purchased.  
2. **Data Scaling**:  
   - Used `StandardScaler` to normalize features.  
3. **Finding Optimal Clusters**:  
   - Evaluated using **Davies-Bouldin Index (DB Index)** and **Elbow Method**.  
   - Optimal clusters: **10** (DB Index = **0.91**).  
4. **Clustering**:  
   - Performed **K-Means clustering** and assigned customers to segments.  
5. **Visualization**:  
   - Used **PCA (Principal Component Analysis)** for 2D visualization.  

---

##  Files in This Repository
- `SaiKiran_Dhulipudi_EDA.pdf` – Report on the Exploratory Data Analysis.
- `SaiKiran_Dhulipudi_EDA.ipynb` – Jupyter Notebook for Exploratory Data Analysis.
- `SaiKiran_Dhulipudi_Lookalike.csv` – CSV file with Lookalike Model results. 
- `SaiKiran_Dhulipudi_Lookalike.ipynb` – Jupyter Notebook implementing Lookalike Model.    
- `SaiKiran_Dhulipudi_Clustering.pdf` – Report on the clustering results.
- `SaiKiran_Dhulipudi_Clustering.ipynb` – Jupyter Notebook for Customer Segmentation.  
  
---


