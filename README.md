Bengaluru House Price Analysis
Project Overview

This project focuses on analyzing the Bengaluru House Prices dataset to uncover key trends and insights in the real estate market. The analysis includes data cleaning, exploratory data analysis (EDA), feature engineering, and visualization to understand factors affecting house prices.

Dataset

The dataset contains information about residential properties in Bengaluru, including:

Location
Size (BHK)
Total Square Feet
Number of Bathrooms
Balcony Count
Price
Objectives

Clean and preprocess the dataset.
Handle missing values and outliers.
Analyze the relationship between house prices and property features.
Identify the most expensive and affordable locations.
Calculate price per square foot.
Generate actionable business insights.
Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Jupyter Notebook
Data Analysis Performed
Data Cleaning
Removed duplicate records
Handled missing values
Standardized data formats
Processed inconsistent square footage values
Exploratory Data Analysis (EDA)
Price distribution analysis
Location-wise price comparison
BHK-wise property analysis
Area vs Price relationship
Outlier detection and removal
Feature Engineering

Created a new feature:

Price Per Square Foot

price_per_sqft = (price * 100000) / total_sqft
Visualizations
Histogram of house prices
Scatter plot of area vs price
Location-wise price comparison
BHK distribution charts
Boxplots for outlier detection
Key Insights
Property prices vary significantly across locations.
Larger properties generally have higher prices.
Location is one of the strongest factors affecting house prices.
Certain areas show unusually high price per square foot values.
Outlier removal improves analysis accuracy.
Project Structure
├── bengaluru_house_prices.csv
├── House_Price_Analysis.ipynb
├── README.md

How to Run
Clone the repository
git clone https://github.com/your-username/bengaluru-house-price-analysis.git
Install required libraries
pip install pandas numpy matplotlib seaborn
Open the Jupyter Notebook and run all cells.
Future Improvements
Build a Machine Learning model for price prediction.
Deploy the model using Flask or Streamlit.
Create an interactive dashboard for real-time analysis.
Author

Viraj Patil

Aspiring Data Analyst | Python | SQL | Statistics | Data Visualization

Suggested Repository Names
bengaluru-house-price-analysis
house-price-analysis
bengaluru-real-estate-analysis
house-price-prediction-analysis
data-analysis-bengaluru-house-prices
