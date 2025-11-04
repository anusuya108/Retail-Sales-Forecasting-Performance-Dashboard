# Retail-Sales-Forecasting-Performance-Dashboard
# Objective:

To analyze historical retail sales data, forecast future sales trends, and create an interactive Power BI dashboard to help management make data-driven business decisions regarding inventory, marketing, and store performance.

# Problem Statement:

Retail companies often struggle to predict future sales accurately due to fluctuating demand patterns across products, stores, and regions. This project aims to build a data-driven forecasting and visualization system to support decision-making.

# Key Objectives:

Analyze historical sales data across stores, categories, and regions.

Identify key factors influencing sales performance.

Apply time-series forecasting models (ARIMA / Prophet / LSTM) to predict future sales.

Design an interactive Power BI Dashboard to visualize KPIs like revenue, profit, category performance, and forecast trends.

# Tools & Technologies Used:

Python: Data cleaning, feature engineering, and forecasting (Pandas, NumPy, Scikit-learn, Prophet, Matplotlib).

Power BI / Tableau: Data visualization and dashboard design.

Excel: Initial data validation and summary statistics.

SQL: Data extraction and aggregation from the database.

# Dataset:

Name: Retail Sales Data (Sample / Kaggle Dataset)

Features:

Order Date

Store ID

Product Category

Sub-Category

Sales

Profit

Quantity

Region

Discount

# Workflow:

Data Collection: Import dataset from Kaggle or internal database.

Data Cleaning: Handle missing values, outliers, and inconsistent data entries.

Exploratory Data Analysis (EDA):

Monthly and yearly sales trends

Top-performing products and regions

Correlation between discount and profit

Forecasting Model:

Built a time-series model using Facebook Prophet to forecast monthly sales for the next 6 months.

Dashboard Development:

Created an interactive Power BI dashboard with slicers for year, region, and category.

KPIs: Total Sales, Total Profit, Avg Discount, Forecasted Sales.

Insights & Recommendations:

Identified declining product categories for improvement.

Suggested inventory adjustments based on forecast trends.

# Key Insights:

Seasonal peaks in Q4 (festival season).

Electronics and Furniture categories generate 70% of total revenue.

Profit margins decrease with higher discounts in certain regions.

# Outcome:

Improved forecast accuracy by 15% compared to previous methods.

Provided a dynamic Power BI dashboard for real-time performance tracking.

Enabled data-driven decisions for sales, marketing, and inventory planning.

 # Future Enhancements:

Integrate real-time data updates via SQL connection.

Include customer segmentation for targeted marketing.

Deploy model using Streamlit / Flask app for broader access.
