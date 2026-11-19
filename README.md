# Day 41 – Customer Segmentation and Product Recommendation

## Project Overview
This project focuses on analyzing customer purchasing behaviour using Python and Machine Learning.

The main goal is to understand customer purchasing patterns, group customers based on their behaviour and explore product recommendation techniques.

## Objectives
- Analyze customer transaction data.
- Understand customer purchasing behaviour.
- Identify different customer groups.
- Apply K-Means clustering.
- Explore product recommendations using Cosine Similarity.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Details
The project uses a sample customer transaction dataset containing:

- CustomerID
- Product
- Quantity
- Price
- Date
- TotalAmount

Dataset contains:
- 20 transactions
- 10 unique customers
- 6 columns after data cleaning

## Project Workflow

### 1. Library Import
Imported the required Python libraries for data analysis and machine learning.

### 2. Dataset Creation
Created a sample transaction dataset containing customer IDs, products, quantities, prices and purchase dates.

### 3. Data Exploration
- Checked dataset information.
- Checked missing values.
- Examined dataset shape.
- Identified customer records.

### 4. Data Cleaning
- Removed duplicate records.
- Converted the Date column into datetime format.
- Calculated total purchase amounts.

### 5. Customer-Level Feature Table
Grouped transaction records by CustomerID and calculated:
- Total Purchases
- Total Quantity
- Total Transactions
- Average Purchase Amount

## Project Results

| Metric | Result |
|---|---:|
| Total Customers | 10 |
| Total Transactions | 20 |
| Total Sales | ₹4,34,000 |
| Missing Values | 0 |
| Dataset Columns | 6 |

## Machine Learning Concepts
- Data Preprocessing
- Feature Engineering
- RFM Analysis
- Feature Scaling
- K-Means Clustering
- Cosine Similarity

## Expected Outcomes
- Understand customer purchasing behaviour.
- Group customers based on their purchasing patterns.
- Identify valuable customer segments.
- Explore product similarities and recommendations.

## Conclusion
This project helped me understand how customer transaction data can be organized and analyzed using Python. I learned how to clean datasets, calculate customer-level features and prepare data for machine learning.

The next stage involves customer segmentation using K-Means clustering and exploring product recommendations using Cosine Similarity.

## Internship Details
**Company:** Veda Technology  
**Internship:** AI/ML Internship  
**Day:** 41  
**Project:** Customer Segmentation and Product Recommendation
