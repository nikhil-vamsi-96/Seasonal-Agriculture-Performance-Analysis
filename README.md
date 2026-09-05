# Seasonal Agriculture Performance Analysis 🌾

## Project Overview

**Seasonal Agriculture Performance Analysis** is a data analytics and visualization project that studies how agricultural performance varies across seasons and crops. The analysis focuses on yield, production, profitability, costs, revenue, resource usage, and relationships among key agricultural variables.

The project uses Python-based exploratory and statistical analysis to convert raw agricultural data into meaningful insights for better agricultural planning, crop selection, and resource allocation.

## Problem Statement

Agricultural performance is influenced by seasonal variations, environmental conditions, farming practices, resource availability, and market conditions. As a result, agricultural outcomes may vary across different seasons.

However, raw agricultural data does not clearly reveal these seasonal patterns, trends, relationships, and variations. The objective of this project is to analyze the agricultural dataset and identify meaningful seasonal differences in agricultural performance using data analytics and visualization techniques.

## Objectives

- Analyze agricultural performance across different seasons.
- Compare crop-wise profitability and production.
- Identify high-performing and low-performing crops.
- Study relationships among important agricultural variables.
- Analyze seasonal differences in yield, production, profit, and water efficiency.
- Detect outliers and measure variability in farm-level performance.
- Generate data-driven insights for agricultural planning and resource allocation.

## Dataset

The dataset contains **4,000 agricultural records** and includes information about farms, crops, seasons, environmental conditions, farming inputs, production, costs, revenue, profit, water usage, and disease/pest risk.

### Key Variables

- `Farm_ID`
- `State`
- `District`
- `Crop`
- `Season`
- `Farm_Area_Hectares`
- `Rainfall_mm`
- `Avg_Temperature_C`
- `Humidity_pct`
- `Sunlight_Hours_Day`
- `Soil_pH`
- `Soil_Moisture_pct`
- `Nitrogen_kg_ha`
- `Phosphorus_kg_ha`
- `Potassium_kg_ha`
- `Irrigation_Method`
- `Fertilizer_kg_ha`
- `Pesticide_Litre_ha`
- `Seed_Quality_Score`
- `Yield_Tonnes_Ha`
- `Production_Tonnes`
- `Market_Price_INR_Tonne`
- `Total_Cost_INR`
- `Revenue_INR`
- `Profit_INR`
- `Water_Used_m3`
- `Water_Efficiency_t_per_1000m3`
- `Disease_Pest_Risk_pct`

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- Jupyter Notebook

## Analysis Performed

### Data Preparation

- Data loading and inspection
- Missing-value checking
- Duplicate checking
- Data-type verification
- Data cleaning and preparation

### Exploratory Data Analysis

- Univariate analysis
- Bivariate analysis
- Distribution analysis
- Categorical analysis
- Descriptive statistics

### Statistical Analysis

- Mean and median
- Standard deviation
- Coefficient of variation
- Skewness analysis
- Correlation analysis
- IQR-based outlier detection

### Seasonal Analysis

The project compares **Kharif, Rabi, and Zaid** seasons based on agricultural performance indicators such as yield, production, profit, and water efficiency.

## Key Findings

### 1. Seasonal Profit Performance

- **Kharif:** Average profit ≈ **₹178,914.65**
- **Rabi:** Average profit ≈ **₹87,689.47**
- **Zaid:** Average profit ≈ **-₹24,804.82**

Kharif recorded the highest average profit, while Zaid recorded an average loss.

### 2. Crop Profitability

- **Sugarcane:** Average profit ≈ **₹817,187.99**
- **Chilli:** Average profit ≈ **₹750,878.34**
- **Cotton:** Average profit ≈ **₹124,546.92**

Wheat, Rice, and Maize recorded negative average profits in the analysis.

### 3. Correlation Analysis

The strongest observed correlation was between **Farm Area and Total Cost**, with a correlation coefficient of approximately **0.962**. This indicates a very strong positive relationship between farm size and total agricultural cost.

### 4. Variability and Outliers

- Profit outliers: **404 observations (10.10%)**
- Production outliers: **333 observations (8.33%)**
- Yield outliers: **302 observations (7.55%)**

The analysis indicates considerable variation in farm-level agricultural performance.

## Visualizations

The project includes visualizations such as:

- Season-wise data distribution
- Crop distribution
- Average profit by season
- Top crops by average profit
- Crop × Season profit heatmap
- Correlation heatmap
- Farm area vs profit
- Production and yield analysis
- Outlier analysis

## End Users

- **Farmers** – identify profitable crops and suitable seasons.
- **Agricultural Planners** – support seasonal planning and resource allocation.
- **Government & Policymakers** – understand agricultural trends and support data-driven decisions.
- **Agribusinesses** – evaluate crop profitability and production patterns.
- **Agricultural Researchers** – study seasonal variations and crop performance.

## Future Scope

- Crop yield prediction using Machine Learning.
- Profitability prediction for different crops and seasons.
- Smart crop recommendation based on soil and weather conditions.
- Real-time weather and rainfall integration.
- IoT-based soil and irrigation monitoring.
- Market price forecasting.
- Interactive Power BI dashboard.
- Farmer-focused web/mobile application.

## Project Files

- `seasonal_agriculture_performance_dataset.csv` – agricultural dataset
- `Seasonal_Agriculture_Performance_Data_Analytics.ipynb` – analysis notebook
- `Major Project_Seasonal Agriculture Performance Analysis.pdf` – project report
- `VOIS_Major_Project_PPT_Submission_Template.pptx` – presentation template

## Conclusion

This project demonstrates how data analytics and visualization can be used to understand seasonal agricultural performance, crop profitability, production variability, and relationships between important agricultural factors. The findings can support data-driven agricultural planning, crop selection, and resource allocation.

## Author

**Nikhil Vamsi Bandaaru**  
Velagapudi Ramakrishna Siddhartha Engineering College

## GitHub Repository

https://github.com/nikhil-vamsi-96/Seasonal-Agriculture-Performance-Analysis
