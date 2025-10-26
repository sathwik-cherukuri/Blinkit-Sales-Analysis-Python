# Blinkit-Sales-Analysis-Python
A comprehensive data analysis project exploring sales performance, key product indicators, and outlet trends within a large e-grocery dataset (Blinkit) using the Python .

## E-Grocery Sales Performance Analysis
Executed an end-to-end data analysis project on 8,523 Blinkit grocery items using Python (Pandas, Matplotlib, Seaborn), cleaning data, calculating core KPIs (e.g., $1.2M+ Total Sales), and visualizing trends across outlet type

## Data Sources
<a href ="https://github.com/sathwik-cherukuri/Blinkit-Sales-Analysis-Python/blob/main/BlinkIT%20Grocery%20Data.xlsx" >Blinkit Data</a>

## Tools
- Technology Used: Python (Pandas, NumPy, Matplotlib, Seaborn)
- Environment : Jupyter Notebook
  
##Key Performance Indicators (KPIs)
- Total Sales
- Average Sales
- Average Item Rating
- Sales by Outlet Establishment Year
- Volume/Transaction Count
  

## process
1 .Data Acquisition & Inspection:
- Loaded the dataset, confirming its scale of 8,523 rows and 12 columns.
- Inspected data types and checked for initial data quality issues.
2 .Data Cleaning & Standardization:
- Handled Missing Data: Identified 1,463 missing values in the Item Weight column (a key step before imputation/modeling).
- Categorical Unification: Standardized the Item Fat Content feature by consolidating five inconsistent entries (LF, low fat, reg, etc.) into two clean categories: 'Low Fat' and 'Regular'.
3 .Key Performance Indicator (KPI) Derivation:
- Calculated fundamental business metrics using pandas aggregation:
- Total Sales (Revenue generated, over $1.2 Million).
- Average Sales (Average value per item, $141.0).
- Average Item Rating (Customer satisfaction, 4/5).
4 .Exploratory Data Analysis (EDA) & Visualization:
- Used Matplotlib and Seaborn to group sales data by Outlet Establishment Year.
- Generated visual charts to illustrate temporal trends in sales performance, providing insights into the contribution of outlets established at different points in time
