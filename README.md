\# Data Mining, Modeling And Analytics Assignment 2

\*\*Student:\*\* Nabyonga Theresa

\*\*Registration Number:\*\* S25m19/040   

\*\*Access Number:\*\* B35752  

\*\*Program:\*\* Master of Science in Data Science and Analytics


\## Overview

This repository contains two data mining projects applying exploratory data analysis, data preprocessing, clustering, anomaly detection and classification techniques.

\## Project 1: Wholesale Customers Clustering

\*\*Objective:\*\*
To analyze customer spending patterns and compare clustering techniques for identifying customer segments.


\*\*Dataset:\*\* 
The Wholesale Customers dataset contains 440 customer records with annual spending across six product categories, together with channel and region information.

\*\*Source:\*\* \[UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/292/wholesale%2Bcustomers)


\*\*Methods:\*\*

\- Exploratory Data Analysis and preprocessing

\- Outlier analysis and feature scaling

\- Hopkins statistic

\- K-Means, Hierarchical and DBSCAN clustering

\- Cluster evaluation and interpretation


\*\*Key Findings:\*\* 
K-Means and Hierarchical clustering identified two broad customer segments: fresh-product-oriented customers and grocery/household-product-oriented customers. K-Means provided the most practical segmentation, while DBSCAN produced less balanced clusters.


\## Project 2: Credit Card Fraud Detection

\*\*Objective:\*\*
To compare statistical, clustering-based and classification-based approaches for identifying potentially fraudulent transactions.

\*\*Dataset:\*\*
The dataset contains 284,807 European credit card transactions from September 2013, including 492 fraudulent transactions. Most input features are anonymized PCA components.

\*\*Source:\*\* \[Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)


\*\*Methods:\*\*

\- Exploratory Data Analysis and data cleaning

\- Robust Z-score statistical baseline

\- MiniBatch K-Means anomaly detection

\- Random Forest classification

\- Average Precision and ROC-AUC evaluation

\- Sensitivity analysis


\*\*Key Findings:\*\* Random Forest achieved the strongest performance, with an Average Precision of 0.8264 and ROC-AUC of 0.9504. It identified 97 fraudulent transactions among the top 100 highest-ranked transactions.


\## Repository Structure

```text

Data-Mining-Assignment/

│

├── Project\_1\_Wholesale\_Customers/

│   ├── wholesale\_customers.ipynb

│   └── requirements.txt

│

├── Project\_2\_Credit\_Card\_Fraud/

│   ├── Credit\_Card\_Fraud\_Detection.ipynb

│   └── requirements.txt

│

├── requirements.txt

├── .gitignore

└── README.md

```

\## How to Run

1\. Clone the repository.

2\. Create and activate a Python virtual environment.

3\. Install dependencies:

```bash

pip install -r requirements.txt

```

4\. Download the datasets from their respective sources and place the CSV files in the main project folder.

5\. Open each notebook in Jupyter Notebook or VS Code and run all cells.

\*\*Note:\*\* The datasets are not included in this repository.

\## Tools and Technologies

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, SciPy and Jupyter Notebook.


\## Responsible Use

The projects are intended for educational and analytical purposes. Fraud detection scores should support further investigation rather than automatically determine whether a transaction is fraudulent.



