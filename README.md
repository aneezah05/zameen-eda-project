# Zameen-EDA-Project
This project performs an in-depth Exploratory Data Analysis (EDA) on property listings from Zameen.com, Pakistan’s largest real estate platform.
The goal is to understand the pricing patterns, property characteristics, market trends, and key insights that influence property value across different property types.

# Project Objectives
Clean and preprocess property listing data

Standardize area measurements and price metrics

Explore relationships between bedrooms, bathrooms, area, and price

Visualize property characteristics

Identify pricing trends by property type

Provide actionable insights and recommendations

# Repository Structure

zameen-eda-project/
├── data/
│   └── Zameen.com.xlsx
├── notebook/
│   └── zameen_eda_final.ipynb
├── outputs/
│   └── visuals/
├── report/
│   └── Zameen_EDA_Insights_Report.pdf
└── README.md

# Data Cleaning & Preprocessing
Converted area units (Marla, Kanal, Sq. Yards) to a uniform unit and same for price

Handled missing values

Handled extreme outliers using IQR method

Extracted new features i.e. Price per Area and Total Rooms

Standardized property types using fuzzy wuzzy

Visualized distributions for all numerical variables

# Key Insights
Property value is primarily determined by its size and its city status

Houses, Farm Houses, and Penthouses represent the high-value luxury segment, while Flats and Portions are affordable market segment.

The majority of properties are designed for families, including around 3 to 5 bedrooms 

# Future Improvements
Add location-based analytics 

Build machine learning models for price prediction

Create interactive dashboards

Add temporal trends if historical data becomes available

Deploy a price recommendation tool

# Final Words
This project helps uncover meaningful patterns in Pakistan’s real estate market using EDA techniques.
The insights can help buyers, sellers, investors, and real estate professionals make data-driven decisions.

**If you find this analysis useful, feel free to star the repository and contribute!**
