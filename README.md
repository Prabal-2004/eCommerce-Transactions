# Customer Segmentation and Lookalike Model

This repository contains the implementation of three main tasks focused on customer data analysis and model building using datasets of customers, products, and transactions. The goal is to perform Exploratory Data Analysis (EDA), develop a Lookalike Model, and implement Customer Segmentation/Clustering to derive meaningful insights and recommendations for business strategy improvement.

## Files Description

### 1. `Customers.csv`
- **CustomerID**: Unique identifier for each customer.
- **CustomerName**: Name of the customer.
- **Region**: Continent where the customer resides.
- **SignupDate**: Date when the customer signed up.

### 2. `Products.csv`
- **ProductID**: Unique identifier for each product.
- **ProductName**: Name of the product.
- **Category**: Product category.
- **Price**: Product price in USD.

### 3. `Transactions.csv`
- **TransactionID**: Unique identifier for each transaction.
- **CustomerID**: ID of the customer who made the transaction.
- **ProductID**: ID of the product sold.
- **TransactionDate**: Date of the transaction.
- **Quantity**: Quantity of the product purchased.
- **TotalValue**: Total value of the transaction.
- **Price**: Price of the product sold.

## Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
- **Objective**: Perform EDA on the provided datasets and derive business insights.
- **Deliverables**:
  - A Jupyter Notebook/Python script containing the EDA code.
  - A PDF report with business insights (maximum 500 words).

### Task 2: Lookalike Model
- **Objective**: Build a Lookalike Model that recommends 3 similar customers based on profile and transaction history.
- **Deliverables**:
  - A “Lookalike.csv” file mapping CustomerID to their top 3 similar customers with similarity scores.
  - A Jupyter Notebook/Python script explaining the model development.

### Task 3: Customer Segmentation / Clustering
- **Objective**: Perform customer segmentation using clustering techniques.
- **Deliverables**:
  - A PDF report with clustering results, including the number of clusters, DB Index, and other relevant metrics.
  - A Jupyter Notebook/Python script containing the clustering code.

## Evaluation Criteria

### Task 1: Exploratory Data Analysis
- **Weightage**: 25%
- **Criteria**: Clean and insightful analysis of data, along with meaningful business insights.

### Task 2: Lookalike Model
- **Weightage**: 30%
- **Criteria**: Model accuracy, similarity scores, and the logic behind the recommendations.

### Task 3: Customer Segmentation / Clustering
- **Weightage**: 30%
- **Criteria**: Clustering logic, DB Index score, and quality of visualizations.

### Business Insights
- **Weightage**: 15%
- **Criteria**: Clear, concise, and actionable business insights.

## Submission Instructions

### 1. GitHub Link
- Upload all the PDF and code files in a public GitHub repository.

### 2. File Naming Convention
- Use the following naming convention for all your files:
  - `FirstName_LastName_EDA.pdf`
  - `FirstName_LastName_EDA.ipynb`
  - `FirstName_LastName_Lookalike.csv`
  - `FirstName_LastName_Lookalike.ipynb`
  - `FirstName_LastName_Clustering.pdf`
  - `FirstName_LastName_Clustering.ipynb`

## Final Note
This assignment requires you to apply data science concepts practically to derive insights that can be used in business strategy. Focus on clean, efficient code and provide meaningful insights to help improve business decisions.

## Project Structure
```bash
├── Customers.csv
├── Products.csv
├── Transactions.csv
├── FirstName_LastName_EDA.pdf
├── FirstName_LastName_EDA.ipynb
├── FirstName_LastName_Lookalike.csv
├── FirstName_LastName_Lookalike.ipynb
├── FirstName_LastName_Clustering.pdf
├── FirstName_LastName_Clustering.ipynb
