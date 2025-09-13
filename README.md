# Analysis-on-Global-Country-Macro-Data-using-ML


# Global Country Macro Dataset – Regression Project

## Overview
This project explores a rich dataset of **macro-economic, demographic, and environmental indicators** collected across 195 countries.  
By applying regression algorithms and neural networks, we aim to **analyze patterns of development** and build predictive models for economic outcomes like GDP.  

The study combines **statistical data analysis** with **machine learning techniques** to uncover relationships between variables such as health, education, population, and sustainability.

## Key Aims
- Compile and process a consistent dataset of global indicators.  
- Examine correlations among economic, social, and demographic factors.  
- Train regression-based models to predict macroeconomic performance.  
- Compare classical machine learning methods with deep learning approaches.  

## Dataset Information
- **Size:** 195 records × 35 attributes  
- **Feature Types:**  
  - *Categorical:* Country, ISO code, capital city, calling code  
  - *Numerical:* GDP, CO₂ emissions, land area, birth rate, unemployment, urban population %, education rates, etc.  
- **Data Notes:**  
  - No missing values  
  - Outliers present in variables like GDP and population  
  - Multicollinearity reduced using **VIF (Variance Inflation Factor)**  

## Data Insights & EDA
- **Histograms / Pie Charts:** Show country-level variations in population and life expectancy.  
- **Pairplots / Heatmaps:** Reveal strong positive link between GDP & education/life expectancy; fertility & birth rates correlate negatively.  
- **Boxplots / Countplots:** Display uneven distribution of GDP and inequality across countries.  

##  Models Applied
- **ANN and XGBoost** stand out as the best-performing models for prediction tasks.

## Observations
- **Top Predictors:** GDP, life expectancy, and education enrollment levels.  
- **Negative Predictors:** High fertility and birth rates reduce GDP outcomes.  
- **Model Comparison:**  
  - **XGBoost** was the strongest traditional model.  
  - **ANN (6-5-4-3-1, 500 epochs)** slightly surpassed XGBoost with **R² = 0.8297**.  
- Ensemble techniques outperformed simple linear models.
  
- The dataset highlights **global inequality** in wealth, healthcare, and education.  
- Machine learning approaches effectively capture cross-country economic patterns.    
- This work can support further analysis in **policy research, forecasting, and development studies**.  

