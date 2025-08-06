# Supermart-Grocery-
Supermart Grocery Sales Analysis
This project analyzes retail sales data for a Supermart grocery chain.
It uses Python for cleaning and exploratory analysis, and Tableau for creating an interactive dashboard.

## Project Structure
Supermart-Analysis

  ├── data_preprocessing.py           # Python script for cleaning & EDA
  
  ├── cleaned_supermart_sales.csv     # Cleaned dataset exported for Tableau
  
  ├── Supermart Dashboard.twb         # Tableau workbook
  
  ├── README.md                       # Project documentation
  
  └── /images                         # Screenshots of dashboard 

 ## Objectives
Clean and preprocess raw sales data.

Explore trends in sales, profit, discounts, and regional performance.

Visualize key metrics in an interactive Tableau dashboard.

## How to Run This Project
Python Data Cleaning and EDA
Dependencies:

pandas

matplotlib

seaborn

pip install pandas matplotlib seaborn

Run the script:
python data_preprocessing.py

## What it does:

Loads the CSV dataset.

Converts date columns.

Checks for missing values and duplicates.

Generates:

Bar charts (Sales/Profit by Category and Region)

Monthly sales trends

Discount vs Profit scatter plot

Exports a cleaned dataset (cleaned_supermart_sales.csv) for Tableau.

## Tableau Dashboard
Open the Tableau workbook (Supermart Dashboard.twb) to view:

1. Sales by Category
   
2.Monthly Sales and Profit Trends

3.Geographic Sales Map

4. Profit by Sub Category Treemap
   
5.Discount vs Profit Scatter Plot

Interactive Filters:

Region selector

Category selector

## Key Insights from Dashboard
1. Sales by Category
2. 
Top-performing category: Eggs, Meat & Fish with ₹2,267K in sales.

Second highest: Snacks at ₹2,238K.

Lowest sales category: Beverages at ₹2,085K.

Observation: Sales across all categories are relatively balanced (₹2,000K – ₹2,300K).

2. Monthly Sales and Profit Trends
   
Strong growth in later months, peaking in the last quarter.

Profit remains lower compared to sales but follows a similar upward trend.

Notable spike: Last quarter (Months 10–12), likely due to festive season or promotions.

3. Profit by Sub-Category
   
Top sub-categories by profit:

Health Drinks – ₹267K

Soft Drinks – ₹258K

Noodles – ₹194K

Breads & Buns – ₹191K

Cookies – ₹191K

Lowest profit items: Rice, Chicken, Organic Fruits, Fresh Vegetables.

Observation: Packaged foods & beverages generate higher profits than staples.

4. Geographic Sales Map
   
Sales concentrated in Southern India.

8 locations missing geographic mapping.

Opportunity: Expand sales in Central, North, and East regions.

5. Discount vs Profit Analysis
   
Positive correlation between discount and profit – Higher discounts drive higher profits.

Most transactions: 5–7% discount and ₹9K–₹13K profit.

High-profit outliers: 8–10% discount with profits ₹15K–₹18K.

Observation: Discounts are boosting sales volume effectively.

Overall Business Recommendations

Increase discounts strategically during festive months to maximize profits.

Focus on high-margin products like health drinks, soft drinks, and snacks.

Improve sales in underperforming categories like staples (rice, pulses, chicken).

Expand presence in non-southern regions for better market coverage.


Screenshots
<img width="831" height="383" alt="image" src="https://github.com/user-attachments/assets/58c6c347-a4ff-4dce-bee2-47a671aa7511" />


## Tools Used

Excel

Python 

Tableau

## Acknowledgments
[Unified Mentor]

Tableau Public

Python Data Community
