# Seasonal Agriculture Performance Analysis

## Project Overview

Seasonal Agriculture Performance Analysis is a data analytics and visualization project that analyzes agricultural performance across different crops, seasons, and regions.

The project uses agricultural, environmental, resource utilization, cost, revenue, and profitability data to identify patterns and factors influencing farm performance.

## Problem Statement

Agricultural performance varies significantly depending on crop type, season, environmental conditions, resource usage, and production costs.

The objective of this project is to analyze agricultural data and identify:

- Seasonal differences in agricultural performance
- Most and least profitable crops
- Relationships between farm area, production, yield, cost, revenue, and profit
- Outliers and variations in agricultural performance
- Opportunities for improving agricultural decision-making

## Objectives

1. Analyze agricultural performance across different seasons.
2. Compare profitability among different crops.
3. Analyze relationships between agricultural variables.
4. Identify outliers and highly variable performance measures.
5. Create meaningful visualizations for data-driven insights.
6. Provide recommendations for improving agricultural productivity and profitability.

## Dataset

The dataset contains **4,000 agricultural records** with information related to farms, crops, seasons, environmental conditions, resources, production, costs, revenue, and profitability.

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
- Jupyter Notebook / Google Colab
- GitHub

## Analysis Performed

### 1. Data Cleaning and Preprocessing

- Data inspection
- Missing-value analysis
- Duplicate checking
- Data type validation
- Statistical summaries

### 2. Exploratory Data Analysis

- Univariate analysis
- Bivariate analysis
- Distribution analysis
- Seasonal comparisons
- Crop-level comparisons

### 3. Profitability Analysis

Average profit was analyzed across seasons and crops.

#### Average Profit by Season

| Season | Average Profit |
|---|---:|
| Kharif | ₹178,914.65 |
| Rabi | ₹87,689.47 |
| Zaid | -₹24,804.82 |

Kharif recorded the highest average profit, while Zaid recorded an average loss.

#### Average Profit by Crop

| Crop | Average Profit |
|---|---:|
| Sugarcane | ₹817,187.99 |
| Chilli | ₹750,878.34 |
| Cotton | ₹124,546.92 |
| Groundnut | ₹44,858.12 |
| Pulses | -₹4,238.05 |
| Maize | -₹83,978.33 |
| Rice | -₹102,213.50 |
| Wheat | -₹123,398.34 |

Sugarcane and Chilli were the most profitable crops in the analyzed dataset, while Wheat, Rice, and Maize recorded negative average profits.

## Key Findings

- Kharif achieved the highest average profit of approximately **₹178,915**.
- Rabi achieved an average profit of approximately **₹87,689**.
- Zaid recorded an average loss of approximately **₹24,805**.
- Sugarcane was the most profitable crop, with an average profit of approximately **₹817,188**.
- Chilli was the second-most profitable crop, with an average profit of approximately **₹750,878**.
- Wheat recorded the lowest average profit at approximately **-₹123,398**.
- Farm area and total cost showed a very strong positive correlation of approximately **0.962**.
- Production and yield showed a strong positive correlation of approximately **0.883**.
- Profit and revenue showed a strong positive correlation of approximately **0.887**.
- Profit showed substantial variability, with **404 outliers (10.10%)** identified using the IQR method.

## Visualizations

The project includes visualizations such as:

- Average Profit by Season
- Crop Profitability Comparison
- Crop × Season Profit Heatmap
- Correlation Heatmap
- Outlier Analysis
- Distribution and statistical analysis charts

## End Users

The analysis can be useful for:

- Farmers
- Agricultural planners
- Agribusiness organizations
- Government agricultural departments
- Researchers
- Data analysts
- Agricultural decision-makers

## Future Scope

Future improvements could include:

- Predictive crop yield modeling
- Crop profitability prediction
- Weather-based agricultural recommendations
- Machine learning for crop selection
- Disease and pest risk prediction
- Real-time agricultural data integration
- Interactive dashboards using Power BI or Tableau
- Regional-level agricultural recommendations

## Project Files

- `Seasonal_Agriculture_Performance_Data_Analytics.ipynb` — Complete analysis notebook
- `seasonal_agriculture_performance_dataset.csv` — Dataset
- `Seasonal_Agriculture_Performance_Analysis_Final.pptx` — Project presentation
- `Major_Project_Seasonal_Agriculture_Performance_Analysis.pdf` — Project report
- `README.md` — Project documentation

## Conclusion

The analysis demonstrates that agricultural profitability varies considerably across seasons and crops.

Kharif showed the strongest overall seasonal performance, while Sugarcane and Chilli were the most profitable crops. The analysis also identified strong relationships between farm area, cost, production, yield, revenue, and profit.

These insights can support data-driven agricultural planning and help improve productivity, resource utilization, and profitability.

## Author

**Nikhil Vamsi Bandaaru**

Velagapudi Ramakrishna Siddhartha Engineering College

## GitHub Repository

[Seasonal Agriculture Performance Analysis](https://github.com/nikhil-vamsi-96/Seasonal-Agriculture-Performance-Analysis)
