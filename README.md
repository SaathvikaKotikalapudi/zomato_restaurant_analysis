# Zomato_restaurant_analysis
# Table of Contents
- Project Overview
- Business Problem
- Dataset Information
- Tools & Technologies
- Data Cleaning
- Exploratory Data Analysis (Excel)
- SQL Business Analysis
- Power BI Dashboard
- Dashboard Preview
- Machine Learning Models
- Model Performance
- Key Insights
- Business Recommendations
- Future Improvements
- Project Structure
- Skills Demonstrated
- Author
# Project Overview
  The restaurant industry is highly competitive, and understanding food trends, customer preferences, and pricing dynamics is crucial for success. For platforms like Zomato, analyzing restaurant data helps optimize business performance, improve customer engagement, and predict restaurant success rates.
This project analyzes Zomato restaurant data to identify key factors influencing restaurant ratings, pricing, and popularity, and builds a machine learning model to predict restaurant success (high vs. low ratings).
This project demonstrates an end-to-end data analytics workflow, including:
- Data Analysis using Excel
- Business Analysis using SQL
- Data Visualization using Power BI
- Machine Learning using Python
# Business Problem
   New and existing restaurants face high failure rates due to a lack of data-driven insights regarding location, pricing, and cuisines.
The objectives of this project are:
- Identify patterns that lead to high customer ratings and reviews
- Analyze customer behavior, spending habits, and online ordering patterns
- Visualize restaurant performance insights using interactive dashboards
- Build a machine learning model to predict restaurant success/rating categories
These insights help restaurant owners and Zomato optimize listings, adjust pricing strategies, and improve customer satisfaction.
# Dataset Information
Dataset used: Zomato Restaurant Dataset
Dataset Source: https://www.kaggle.com/datasets/shrutimehta/zomato-restaurants-data (or relevant Zomato Kaggle link)
The dataset contains comprehensive information about various restaurants listed on Zomato.
Key features include:
- Restaurant Name & ID
- City / Locality
- Cuisines Offered
- Average Cost for Two
- Has Table Booking (Yes/No)
- Has Online Delivery (Yes/No)
- Aggregate Rating
- Votes / Reviews
- Price Range
Dataset files used in this project:
01_Data
- zomato-restaurants-train.csv
- zomato-restaurants-test.csv
# Tools & Technologies
- Excel – Exploratory Data Analysis & Pivot Tables
- SQL – Business analysis queries & data extraction
- Power BI – Interactive dashboard visualization
- Python – Data preprocessing, feature engineering, and machine learning
- Scikit-Learn – Model Training & Evaluation
# Data Cleaning
  Before performing analysis, the dataset was validated, cleaned, and prepared.
Steps performed:
- Handled missing values (e.g., missing cuisines or text reviews)
- Cleaned and standardized text data (e.g., stripping extra spaces from city/cuisine names)
- Converted data types (e.g., pricing and ratings converted to numeric formats)
- Dropped duplicate restaurant entries to ensure data consistency
- The cleaned dataset was then utilized for further downstream analysis.
# Exploratory Data Analysis (Excel)
  Exploratory Data Analysis (EDA) was performed using Excel pivot tables and charts.
Key analysis performed:
- Distribution of restaurant ratings across major cities
- Impact of online delivery availability on total votes
- Correlation between average cost for two and overall ratings
- Most popular cuisine types based on restaurant counts
- Excel helped in identifying initial trends and generating quick data summaries.
Excel File Location:
      02_Excel_EDA
    Telecom_Churn_EDA.xlsx
