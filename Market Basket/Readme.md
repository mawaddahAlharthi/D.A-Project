# Project Title
Online Retail Market Basket Analysis

## Project Overview
This project performs Market Basket Analysis (MBA) using transaction data from an online retail store. Market Basket Analysis is a data mining technique used to discover associations between products that are frequently bought together. Insights from this analysis can help optimize inventory management, plan effective sales promotions, and design personalized product recommendations. In this project, we employ the Apriori algorithm to identify frequent itemsets and generate association rules.

## Dataset 
- **Dataset Name**: OnlineRetail.csv
- **Source**: [Kaggle Notebook](https://www.kaggle.com/code/hassanamin/market-basket-analysis-for-online-retail-dataset/notebook)
- **File Format**: CSV
- **Encoding**: latin1

## Libraries Used
The following Python libraries are required to run the code successfully:
- **pandas**: For data loading and manipulation.
- **mlxtend**: To apply Market Basket Analysis using the Apriori algorithm and association rules.
- **numpy**: For numerical operations.
- **matplotlib** or **seaborn**: For visualizing data insights.

## How to Run the Code
### Step 1: Clone or Download the Repository
- Download the project files or clone the repository to your local machine.

### Step 2: Place the Dataset
- Place the `OnlineRetail.csv` file in the project folder.

### Step 3: Execute the Python Script
Run the provided Python script to conduct Market Basket Analysis with the Apriori algorithm. The script will:
- Load the dataset using pandas.
- Preprocess the data by grouping items by invoice number and handling duplicates.
- Apply one-hot encoding to prepare data for analysis.
- Run the Apriori algorithm to find frequent itemsets.
- Generate association rules that reveal relationships between commonly bought items.

### Step 4: View the Results
- After execution, the script displays the top 10 association rules, highlighting items that are frequently bought together. You can adjust the support and confidence thresholds to refine the results based on specific analysis needs.

## How the Dataset Was Used
### 1. Data Preprocessing:
- Transactions were grouped by `InvoiceNo` to aggregate items purchased together.
- One-hot encoding transformed the dataset into a format suitable for the Apriori algorithm.

### 2. Market Basket Analysis:
- The Apriori algorithm identified frequent itemsets with a minimum support threshold of 1%.
- Association rules were generated to discover product relationships with a minimum lift threshold of 0.5.

### 3. Analysis Goal:
- The primary goal is to identify relationships between products frequently purchased together, which can support decision-making for inventory management, sales promotions, and recommendation systems.
