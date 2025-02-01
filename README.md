# eCommerce-Transaction
# Data Science Intern Assignment

This repository contains the solution to the Data Science Intern Assignment, which includes **Exploratory Data Analysis (EDA)**, **Lookalike Model Development**, and **Customer Segmentation** tasks for an eCommerce transactions dataset.

---

## 📋 Project Overview

The assignment involves analyzing an eCommerce dataset (`Customers.csv`, `Products.csv`, `Transactions.csv`) to derive business insights, build a customer similarity model, and perform customer segmentation using clustering techniques. The tasks are structured as follows:

1. **Task 1**: Exploratory Data Analysis (EDA) and Business Insights  
2. **Task 2**: Lookalike Model for Customer Recommendations  
3. **Task 3**: Customer Segmentation via Clustering  

---

## 🚀 Repository Structure

├── data/ # Raw data files (not included in repo)
│ ├── Customers.csv
│ ├── Products.csv
│ └── Transactions.csv
├── output/ # Generated output files
│ ├── Lookalike.csv
│ ├── EDA_Report.pdf
│ └── Clustering_Report.pdf
├── notebooks/ # Jupyter notebooks for each task
│ ├── FirstName_LastName_EDA.ipynb
│ ├── FirstName_LastName_Lookalike.ipynb
│ └── FirstName_LastName_Clustering.ipynb
├── README.md # This file
└── requirements.txt # Python dependencies


---

## 📂 Dataset Details

The dataset consists of three files:
1. **Customers.csv**: Customer demographics (e.g., `CustomerID`, `Region`, `SignupDate`).  
2. **Products.csv**: Product details (e.g., `ProductID`, `Category`, `Price`).  
3. **Transactions.csv**: Transaction records (e.g., `TransactionID`, `CustomerID`, `TotalValue`).  

⚠️ **Note**: Download the dataset from the links provided in the problem statement and place the files in the `data/` directory.

---

## 🛠️ Tasks and Deliverables

### **Task 1: EDA and Business Insights**
- **Goal**: Explore the dataset and derive actionable insights.  
- **Deliverables**:  
  - `FirstName_LastName_EDA.ipynb`: Jupyter notebook with code for EDA.  
  - `EDA_Report.pdf`: PDF report summarizing 5 business insights (e.g., customer signup trends, sales by category).  

### **Task 2: Lookalike Model**
- **Goal**: Recommend 3 similar customers for the first 20 customers.  
- **Deliverables**:  
  - `FirstName_LastName_Lookalike.ipynb`: Code for merging data, feature engineering, and cosine similarity.  
  - `Lookalike.csv`: CSV file mapping `CustomerID` to recommended customers and scores.  

### **Task 3: Customer Segmentation**
- **Goal**: Cluster customers using K-means and evaluate clusters.  
- **Deliverables**:  
  - `FirstName_LastName_Clustering.ipynb`: Code for clustering, DB Index calculation, and visualization.  
  - `Clustering_Report.pdf`: PDF report with cluster metrics (DB Index, Silhouette Score) and visualizations.  

## ⚙️ How to Run

1. **Install Dependencies**:
   ```bash
pip install -r requirements.txt
Required libraries: pandas, scikit-learn, matplotlib, seaborn, jupyter.

Prepare Data:

Download the dataset from the provided links.

Place Customers.csv, Products.csv, and Transactions.csv in the data/ folder.

Run Jupyter Notebooks:

Execute the notebooks in the following order:

FirstName_LastName_EDA.ipynb

FirstName_LastName_Lookalike.ipynb

FirstName_LastName_Clustering.ipynb

Generated files (PDFs, CSV) will be saved in the output/ directory. do I need to include this also inside the read me file
